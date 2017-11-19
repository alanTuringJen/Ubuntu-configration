# 安装好Ubuntu系统后的基本操作
###### 安装必要的命令
    sudo apt install <>
    vim python3 geany chromium-browser...

###### 更新源（阿里云）
    sudo vim /etc/apt/source.list
    sudo apt-get update
    sudo apt-get upgrade

source:
http://blog.csdn.net/fengyuzhiren/article/details/54844870

###### 换主题
1.Install unity-tweak-tool

    sudo apt install unity-tweak-tool
2. Install theme called Flatabulous 

        sudo add-apt-repository ppa:noobslab/themes
        sudo apt-get update
        sudo apt-get install flatabulous-theme

3. Install some icons from this theme（主题）
    
        sudo add-apt-repository ppa:noobslab/icons
        sudo apt-get update
        sudo apt-get install ultra-flat-icons

4. 打开unity-tweak-tool软件，修改主题为flatabulous图标为ultra-flat

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

