# NLP-3b

>  Course materials of Natural Language Processing

**Repo:** [Streamer0320/NLP-3b | GitHub](https://github.com/Streamer0320/NLP-3b/) 

**Fork:** [jin-hao-0320/NLP-3b | Gitee](https://gitee.com/jin-hao-0320/NLP-3b) 


**在更新第十二个实验文档后，该项目所有实验内容上传基本完成，部分实验我会把 `ipynb` 和相关文件资源以压缩打包的形式按照章节发布，以方便下载和操作。**


## 🔎 简 介

本仓库内容基于 `usyiyi/nlp-py-2e-zh` 仓库内容，使用 `jupyter notebook` 重新排版为便于操作的 `.ipynb` 文件，并对无法正常运行的部分代码和有变化的内容做了修改。

由于前期 `ipynb` 文件的目录跳转是优先基于 `jupyter notebook` 场景进行配置的，可能无法完全支持部分非 `jupyter notebook` 软件的某些场景（例如 `vscode 的 jupyter 插件`）。


## 📃 目 录

1. [语言处理与Python](./1.语言处理与Python.ipynb)
2. [获得文本语料和词汇资源](./2.获得文本语料和词汇资源.ipynb)
3. [处理原始文本](./3.处理原始文本.ipynb)
4. [编写结构化的程序](./4.编写结构化程序.ipynb)
5. [分类和词汇标注](./5.分类和词汇标注.ipynb)
6. [学习分类文本](./6.学习分类文本.ipynb)
7. [从文本提取信息](./7.从文本提取信息.ipynb)
8. [分析句子结构](./8.分析句子结构.ipynb)
9. [构建基于特征的文法](./9.构建基于特征的语法.ipynb)
10. [分析句子的含义](./10.分析句子的意思.ipynb)
11. [语言学数据管理](./11.语言学数据管理.ipynb)
12. [后记︰面对语言的挑战](./12.后记：语言的挑战.ipynb)



## 📦 环 境

- Operating System: `Windows 10 (64-bits) 22H2` 

- Platform: `Acaconda3 (64-bits)` 

- Python Version: `3.8.16` 

- requirements.txt: [requirements.txt](./requirements.txt) 

- Dataset ：[NLTK_Data | GitHub](https://github.com/nltk/nltk_data) OR [NLTK_Data Mirror | Gitee](https://gitee.com/lanyan324/nltk_data)  




## 🧐 配 置

**Windows 10 or 11**

1. 确保你电脑上已经安装了 Acaconda3 (64-bits)。

2. <kbd>Win</kbd>+<kbd>R</kbd> 输入 "cmd" 并 <kbd>Enter</kbd> 回车，或者打开 `Anaconda Powershell Prompt  (Anaconda3)` 命令行工具。

3. 使用以下命令创建 Python 虚拟环境：

   ```
   conda create -n nltk python=3.8
   ```

4. 使用以下命令进入虚拟环境：

   ```
   conda activate nltk
   ```

5. 使用以下命令用 `requirements.txt` 文件配置环境：

   ```
   conda install --yes --file requirements.txt
   ```

6. 或者直接使用以下命令完成 3、4、5 步：

   ```
   conda create --name nltk --file requirements.txt
   ```

7. 如果有疑问，请参阅以下详细的配置说明文件。

   [Python-NLTK环境配置.ipynb](./NLTK环境配置.ipynb)

## 🔗 参 考

- nlp-py

https://www.nltk.org/book/

https://usyiyi.github.io/nlp-py-2e-zh/

- environment base

https://www.anaconda.com

- nltk

https://mirrors.bfsu.edu.cn/anaconda/pkgs/main/

https://www.nltk.org/

https://github.com/nltk/nltk

- nltk_data

https://github.com/nltk/nltk_data

- md2ipynb

https://github.com/aaren/notedown

- megam iis

https://stackoverflow.com/questions/12606543/nltk-megam-max-ent-algorithms-on-windows

- prover9 mace4

https://blog.csdn.net/gdkyxy2013/article/details/88377848

https://www.cs.unm.edu/~mccune/prover9/

https://www.nltk.org/howto/inference.html

https://stackoverflow.com/questions/25844794/nltk-was-unable-to-find-mace4/44805638

- maltparser

https://github.com/nltk/nltk/wiki/Installing-Third-Party-Software#malt-parser

http://www.maltparser.org/download.html

- `engmalt.linear-1.7.mco`

http://www.maltparser.org/mco/mco.html
