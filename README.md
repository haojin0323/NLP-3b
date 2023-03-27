# NLP-3b

>  Course materials of Natural Language Processing

repo: [Streamer0320/NLP-3b | GitHub](https://github.com/Streamer0320/NLP-3b/)

fork: [jin-hao-0320/NLP-3b | Gitee](https://gitee.com/jin-hao-0320/NLP-3b)



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
8. 分析句子结构
9. 构建基于特征的文法
10. 分析句子的含义
11. 语言学数据管理
12. 后记︰面对语言的挑战



## 📦 环 境

- Operating System: `Windows 10 (64-bits) 22H2` 
- Platform: `Acaconda3 (64-bits)` 
- Python Version: `3.8.16` 
- requirements.txt: [requirements.txt](./requirements.txt) 

- Dataset ：[NLTK Data | GitHub](https://github.com/nltk/nltk_data) 

​						  [NLTK_Data Mirror | Gitee](https://gitee.com/lanyan324/nltk_data)  



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
6. 如果有疑问，请参阅以下详细的配置说明文件。
   

​	[Python-NLTK环境配置.ipynb](./NLTK环境配置.ipynb)



## 🔧 更 新

- v0.7.0	2023-03-27

1. 把 7.html 原始内容整理到 `ipynb` 文件并排版；
2. 添加了支持 `jupyter notebook` 和 `vscode jupyter` 的目录；
3. 运行代码更正错误并添加注释；
4. 上传文件 `7.从文本提取信息.ipynb` ；
5. 更新了 `README.md` ;




- v0.6.2	2023-03-22

1. 上传了 `conda` 环境的 `requirements.txt` 

2. 在 `6.ipynb` 中添加了实验环境信息。 



- v0.5.1    2023-03-22

1. 在 `5.ipynb` 中添加了实验环境信息。 



- v0.6.1	2023-03-19

1. 修改了 `README.md` 的部分信息。



- v0.6.0	2023-03-19

1. 把 6.html 原始内容整理到 `ipynb` 文件并排版；
2. 添加了支持 `jupyter` 的目录；
3. 运行代码更正错误并添加注释；
4. 上传文件 `6.学习分类文本.ipynb` ；
5. 更新了 `README.md` ;



- v0.4.1	2023-03-13

1. 更新了 4.ipynb 文件的目录



- v0.5.0	2023-03-10

1. 把 5.html 原始内容整理到 `ipynb` 文件并排版；
2. 添加了支持 `jupyter` 的目录；
3. 运行代码更正错误并添加注释；
4. 上传文件 `5.分类和词汇标注.ipynb` ；
5. 更新了 `README.md` ;



- v0.4.0	2023-03-10

1. 把 4.html 原始内容整理到 `ipynb` 文件并排版；
1. 运行代码并更正错误；
1. 添加了支持 `jupyter` 的目录和注释；
1. 上传文件 `4.编写结构化程序.ipynb` ;
1. 更改了版本规则；
1. 更新了说明文件；



- v0.3.0	2023-03-06

1. 把 3.html 原始内容整理到 `ipynb` 文件并排版；
2. 修改了原始代码运行时出现的报错内容；
3. 在代码段添加了更多的注释；
4. 上传文件 `3 处理原始文本.ipynb` ；
5. 修改 README 链接目录为相对路径目录



- v0.2.2	2023-03-06

1. 在第二章添加了 html 标签章节目录；
1. 更新了全图 `nltk` 环境配置说明；
1. 上传了 `nltk` 配置中提到的两个包，目录： `./asset` ；
1. 修改了测试分支的过程中产生的错误；



- v0.2.1	2023-03-06

1. 更新并简化了文件命名；
2. 添加了 `nltk` 镜像源安装方法和离线安装方法说明文件；
5. 更新 `README.md` ;
6. 在 `Gitee` 平台 `fork` 了该库以方便访问；



- v0.2.0	2023-02-27

1. 把 2.html 原始内容整理到 `ipynb` 文件并排版；
2. 修改了原始代码运行时出现的报错内容；
3. 在代码段添加了更多的注释；
4. 上传文件 `2.获得文本语料和词汇资源-添加注释.ipynb` ；
5. 更新 `README.md` ;



- v0.1.0	2023-02-25

1. 把 1.html 原始内容整理到 `ipynb` 文件并排版；
2. 修改了原始代码运行时出现的报错内容；
3. 在代码段添加了更多的注释；
4. 上传文件 `1.语言处理与Python-添加注释.ipynb` ；
5. 更新 `README.md` ;



## 🔗 参 考

https://usyiyi.github.io/nlp-py-2e-zh/

https://www.anaconda.com

https://mirrors.bfsu.edu.cn/anaconda/pkgs/main/

https://www.nltk.org/

https://github.com/nltk/nltk

https://github.com/nltk/nltk_data

https://github.com/aaren/notedown

https://stackoverflow.com/questions/12606543/nltk-megam-max-ent-algorithms-on-windows

