# Packages Details

> 这里是一些在实验中需要使用但是可能无法使用 `conda install` 直接安装的包

## 目录结构

packages
├—— pip
└—— conda
    ├—— nltk-3.4.5-py38_0.conda
    ├—— six-1.15.0-py38haa95532_0.conda





## 干净安装

一些配置环境的安装命令，干净安装

```
conda install nltk numpy matplotlib

conda install -c anaconda beautifulsoup4

conda install -c anaconda pillow

conda install -c anaconda requests
```



有特殊要求的安装包，安装前请参考说明：

```
pip install flair==0.5

conda install -c conda-forge python-flair
```



## 其他说明

在 4.ipynb 文件中有以下一段代码（原始代码）：

```
from flair.data_fetcher import NLPTaskDataFetcher

data = load_corpus()
results = analyze(data)
present(results)
```

其中 NLPTaskDataFetcher 只在 flair==0.5 可正常导入，由于该包后续版本有一些代码更改，导致以上代码无法正常稳定运行。目前已知可能是一些方法和模块更改了路径和名字，以及由于版权原因下架了一些数据集。
