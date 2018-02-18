# 安装好Ubuntu系统后的基本操作
###### 安装必要的命令
        sudo apt install <>
        vim python3 geany chromium-browser...

###### 更新源（阿里云）
        sudo vim /etc/apt/source.list
        sudo apt-get update
        sudo apt-get upgrade

source:
From: http://blog.csdn.net/fengyuzhiren/article/details/54844870

        # deb cdrom:[Ubuntu 16.04 LTS _Xenial Xerus_ - Release amd64 (20160420.1)]/ xenial main restricted
        deb http://mirrors.tuna.tsinghua.edu.cn/ubuntu/ xenial main restricted
        deb http://mirrors.tuna.tsinghua.edu.cn/ubuntu/ xenial-updates main restricted
        deb http://mirrors.tuna.tsinghua.edu.cn/ubuntu/ xenial universe
        deb http://mirrors.tuna.tsinghua.edu.cn/ubuntu/ xenial-updates universe
        deb http://mirrors.tuna.tsinghua.edu.cn/ubuntu/ xenial multiverse
        deb http://mirrors.tuna.tsinghua.edu.cn/ubuntu/ xenial-updates multiverse
        deb http://mirrors.tuna.tsinghua.edu.cn/ubuntu/ xenial-backports main restricted universe multiverse
        deb http://mirrors.tuna.tsinghua.edu.cn/ubuntu/ xenial-security main restricted
        deb http://mirrors.tuna.tsinghua.edu.cn/ubuntu/ xenial-security universe
        deb http://mirrors.tuna.tsinghua.edu.cn/ubuntu/ xenial-security multiverse

###### Change theme and icon
1.Install unity-tweak-tool

        sudo apt install unity-tweak-tool
2. Install Flatabulous theme

        sudo add-apt-repository ppa:noobslab/themes
        sudo apt-get update
        sudo apt-get install flatabulous-theme

3. Install some icons
   
        sudo add-apt-repository ppa:noobslab/icons
        sudo apt-get update
        sudo apt-get install ultra-flat-icons

4. Open unity-tweak-tool, then change theme to flatabulous and icon to ultra-flat.

###### 卸载LibreOffice

        sudo apt remove libreoffice-common
安装网易云音乐、搜狗输入法、wpsOffice
下载相应的deb包

        sudo dpkg -i <>
        sudo apt install -f

调整中文输入

        sudo apt install fcitx
language support中下载中文包，最低端选择fcitx
在Text Entry中加入sougou pinyin

