# Asset

> 这里是一些在实验中需要使用的文件或者包

## 目录结构

asset
├—— packages
|    	├—— nltk-3.4.5-py38_0.conda
|    	└—— six-1.15.0-py38haa95532_0.conda
├—— dict.csv
├—— engmalt.linear-1.7.mco
├—— maltparser-1.7.zip
├—— megam-64.opt
├—— mygrammar.cfg
├—— Prover9-Mace4.zip
├—— Prover9-Mace4-v05-setup.exe
└—— README.md





## 环境配置

配置 NLTK 环境，干净安装的命令

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



## 说明

在 4.ipynb 文件中有以下一段代码（原始代码）：

```
from flair.data_fetcher import NLPTaskDataFetcher

data = load_corpus()
results = analyze(data)
present(results)
```

其中 NLPTaskDataFetcher 只在 flair==0.5 可正常导入，由于该包后续版本有一些代码更改，导致以上代码无法正常稳定运行。目前已知其无法运行的原因是该包的一些方法和模块更改了路径和名字，并且作者说由于版权原因去除了部分数据集（需要去相应的官方网站自己下载）。
