# Latex-vscode
This is a repository for latex settings in vscode

# Repository

Github: https://github.com/Hydraallen/Latex-vscode

# Downloads
+ vscode: https://code.visualstudio.com/
+ Texlive: (choose one)
  + https://tug.org/texlive/acquire-iso.html
  + https://mirrors.cloud.tencent.com/CTAN/systems/texlive/Images/
  + https://mirrors.tuna.tsinghua.edu.cn/CTAN/systems/mac/mactex/
+ SumatraPDF: https://www.sumatrapdfreader.org/free-pdf-reader



# Installation

## Windows

Video for Reference->https://www.bilibili.com/video/BV1wP411f7gG/

1. Install Texlive （about 4G）

Download -> https://mirrors.tuna.tsinghua.edu.cn/CTAN/systems/texlive/Images/texlive.iso

![](https://raw.githubusercontent.com/Hydraallen/images/master/img/Snipaste_2023-03-18_01-10-17.png)

Run as asministrator

![](https://raw.githubusercontent.com/Hydraallen/images/master/img/Snipaste_2023-03-18_01-33-41.png)

Wait for finish

![](https://raw.githubusercontent.com/Hydraallen/images/master/img/Snipaste_2023-03-18_01-38-01.png)

Test installation

Open cmd or Powershell and type in `tex -v`, if shows information like picture below then it means texlive has been installed.

![](https://raw.githubusercontent.com/Hydraallen/images/master/img/WechatIMG359.png)

2. Install VScode and Latex Workshop

![](https://raw.githubusercontent.com/Hydraallen/images/master/img/latex-windows-%E5%AE%8C%E6%95%B4%E6%97%A0%E5%AD%97%E5%B9%95-0002.png)

edit `settings.json` (You may refer to `vscode-settings.json` in repository`Latex-vscode/Windows` and refer to the video)

3. Install SumatraPDF (optional)

## macOS

（It applies to both Intel and Apple Silicon）

Video for Reference->https://www.bilibili.com/video/BV1DM4y1z71m

1. Install MacTex

First check your system version

![](https://raw.githubusercontent.com/Hydraallen/images/master/img/WechatIMG1497.png)

![](https://raw.githubusercontent.com/Hydraallen/images/master/img/Snipaste_2023-05-22_21-32-19.png)

### option 1

Download MacTex on http://tug.org/mactex/

![](https://raw.githubusercontent.com/Hydraallen/images/master/img/Snipaste_2023-03-18_23-24-39.png)



Choose one according to your system.

Remember to check `md5` for `MacTex.pkg`

![](https://raw.githubusercontent.com/Hydraallen/images/master/img/Snipaste_2023-03-18_23-35-50.png)

Install `MacTex.pkg`

![](https://raw.githubusercontent.com/Hydraallen/images/master/img/Snipaste_2023-03-18_23-29-53.png)



### option 2

Install with [`homebrew`](https://brew.sh/). If you fail to connect to the official website, you may try [mirror](https://mirrors.tuna.tsinghua.edu.cn/help/homebrew/).

```
brew install mactex --cask
```



Test `MacTex.pkg`

![](https://raw.githubusercontent.com/Hydraallen/images/master/img/Snipaste_2023-03-18_23-38-58.png)

2. Install VScode  and Latex Workshop

https://code.visualstudio.com/

![](https://raw.githubusercontent.com/Hydraallen/images/master/img/Snipaste_2023-03-18_23-44-40.png)

3. edit `setting.json` in VScode

*You may refer to `Latex-vscode/Linux/vscode-setting.json`in the repository*

![](https://raw.githubusercontent.com/Hydraallen/images/master/img/Snipaste_2023-03-18_23-47-34.png)

Remember to change the route of Xelatex, PDFLatex, etc.

![](https://raw.githubusercontent.com/Hydraallen/images/master/img/Snipaste_2023-03-18_23-48-40.png)

4. testfile

![](https://raw.githubusercontent.com/Hydraallen/images/master/img/Snipaste_2023-03-18_23-50-14.png)



## Linux

### Arch/Manjaro

article for reference -> https://www.bilibili.com/read/cv22494481

1. Install VScode and install `Latex Workshop` in VScode

```
yay -S visual-studio-code-bin
```



2. Install TexLive

```
yay -S texlive-full
```



![](https://raw.githubusercontent.com/Hydraallen/images/master/img/WechatIMG379.jpeg)

use `tex -v` to test

![](https://raw.githubusercontent.com/Hydraallen/images/master/img/WechatIMG376.png)

3. edit `setting.json` in VScode

*You may refer to `Latex-vscode/Linux/vscode-setting.json`in the repository*

![](https://raw.githubusercontent.com/Hydraallen/images/master/img/WechatIMG375.png)

Remember to change the route of Xelatex, PDFLatex, etc.

![](https://raw.githubusercontent.com/Hydraallen/images/master/img/Snipaste_2023-03-18_23-18-55.png)

4. testfile

![](https://raw.githubusercontent.com/Hydraallen/images/master/img/WechatIMG378.png)



### **debina/ubuntu**

Run `sudo apt-get install texlive-full`

# Reference

https://zhuanlan.zhihu.com/p/166523064

https://github.com/James-Yu/LaTeX-Workshop/wiki/Compile#placeholders

https://mp.weixin.qq.com/s/GxYrbhxiv7bIG5Ulr2XetQ

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Hydraallen/Latex-vscode&type=Date)](https://star-history.com/#Hydraallen/Latex-vscode&Date)
