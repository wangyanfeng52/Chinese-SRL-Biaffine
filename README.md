# Chinese-SRL-Biaffine

此仓库包含论文《Improved Biaffine Method for Chinese Semantic Role Labeling》的代码和数据。

## 📚 论文信息

* **论文标题**: Improved Biaffine Method for Chinese Semantic Role Labeling

* **作者**: MA Ning, WANG Jiahao

* **期刊**: PLOS ONE (2025)

## 📂 仓库内容说明

* `code.zip`: 实验代码压缩包，包括训练和评估模型的脚本。

* `data.zip`: 数据集压缩包（中文语义角色标注CPB语料子集）。

## 🔧 环境需求

* Python 3.8 或更新版本

* PyTorch 1.10 或更新版本

* Transformers (HuggingFace)

* numpy, pandas, tqdm 等依赖库

## 🚀 快速开始（使用说明）

&#x20;

① 克隆仓库：

```
git clone https://github.com/wangyanfeng52/Chinese-SRL-Biaffine.git
cd Chinese-SRL-Biaffine
```

② 解压代码与数据：

```
unzip code.zip -d ./code
unzip data.zip -d ./data
```

③ 安装Python依赖：

```
cd code
pip install -r requirements.txt
```

④ 模型训练：

```
python train.py
```

⑤ 模型评估：

```
python evaluate.py --model_path 你的模型路径
```

## 📈 模型性能对比

| 模型                                | F1值 (%) |
| :-------------------------------- | :------ |
| BiLSTM-Att-CRF (Zhu et al., 2021) | 81.41   |
| RoBERTa-MPBF (我们的模型)              | 90.89   |

## 📦 数据公开链接

本文数据与代码已在本仓库中公开：

https://github.com/wangyanfeng52/Chinese-SRL-Biaffine

## 📖 引用方式

如果你使用本仓库的代码或数据，请引用我们的论文：

```
@article{Ma2025Improved,
  author = {Ma, Ning and Wang, Jiahao},
  title = {Improved Biaffine Method for Chinese Semantic Role Labeling},
  journal = {PLOS ONE},
  year = {2025},
  volume = {},
  number = {},
  pages = {},
  doi = {},
}
```

## 📜 许可证

本项目代码和数据均采用 MIT 许可证开源，可自由使用与修改。

## 📧 联系方式

* 通讯作者：MA Ning

* 邮箱：maning8162@163.com

```
```

