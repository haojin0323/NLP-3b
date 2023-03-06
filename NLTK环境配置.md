# NLTK 环境配置

## 清华源 Anaconda 镜像使用帮助

Anaconda 安装包可以到 https://mirrors.tuna.tsinghua.edu.cn/anaconda/archive/ 下载。

### 1. 生成配置文件

Windows 用户可先在 `cmd` 执行 `conda config --set show_channel_urls yes` ，可在用户目录查看生成的 `.condarc` 配置文件。

### 2. 打开配置文件

在 Windows 系统中，该文件位于目录：`C:\Users\%USERNAME%\.condarc` ，通过修改该文件内容使用 TUNA 镜像源。

### 3. 修改配置文件

使用以下内容替换 .condarc 文件内容。
```
channels:
  - defaults
show_channel_urls: true
default_channels:
  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main
  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/r
  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/msys2
custom_channels:
  conda-forge: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  msys2: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  bioconda: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  menpo: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  pytorch: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  pytorch-lts: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  simpleitk: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
```
即可添加 Anaconda Python 免费仓库。

> 注：由于更新过快难以同步，我们不同步`pytorch-nightly`, `pytorch-nightly-cpu`, `ignite-nightly`这三个包。

### 4. 使用配置文件

在 `cmd` 运行 `conda clean -i` 清除索引缓存，保证用的是镜像站提供的索引。

### 5. 环境配置

镜像配置完成，现在可以进入虚拟环境并使用以下代码配置环境了，运行 `conda create -n myenv numpy` 测试一下吧。


## 离线安装 Python 包

> 为保证python包和Python版本兼容，最好创建一个同版本Python的虚拟环境。

### 1. 访问镜像网站

进入镜像网址并选择自己电脑系统型号，示例如下：

https://mirrors.bfsu.edu.cn/anaconda/pkgs/main/

### 2. 搜索对应版本包

根据自己创建的虚拟环境选择对应版本的包，使用 `Ctrl + F` 搜索并下载对应 python 版本的后缀为 `.conda` 的包 。

### 3. 安装离线包

在下载包的目录文件夹打开 `cmd` 并进入虚拟环境，使用以下命令安装。（以下为示例，填写自己下载的包名）

```bash
# 在安装 nltk 离线环境时至少需要安装 nltk 和 six 两个离线包，请根据 python 版本进行下载安装
conda install --use-local nltk-3.4.5-py38_0.conda
```

> **说明：** 离线安装包时，可能会报错缺失额外的包，此时根据报错内容按照以上步骤继续配置相应包即可。