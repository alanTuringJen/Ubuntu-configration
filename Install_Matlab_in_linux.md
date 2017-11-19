# Install
Matlab R2016b for linux
下载地址：https://pan.baidu.com/s/1chCYD4   密码: qhgk

###### 下载好之后，会有三个文件：
    Matlab 2016b Linux64 Crack.rar
    R2016b_glnxa64_dvd1.iso
    R2016b_glnxa64_dvd2.iso

###### 挂载iso文件(先将上述三个文件放在 ~ 目录下）：
    cd ~
    mkdir matalb
    sudo mount -t auto -o loop R2016_glnxa64_dvd1.iso matlab/
挂载成功后，会多一个盘
然后：

    cd matlab/
    sudo ./install

安装到 80percent 左右时，会提示插入dvd2

    cd ~
    sudo mount -t auto -o loop R2016_glnxa64_dvd2.iso matlab/

然后在提示插入dvd2的地方单机确定即可。

###### 安装完成之后，取消 iso 挂载：
    cd ~
    umount matlab/
自行删除安装包以及文件夹

# Cracking
    cd /usr/local/MATLAB/R2016b/bin
    sudo ./matlab

###### First
载入激活文件license_standalone.lic（根据Crack文件夹中的readme.txt文件中的提示自己调整文件）
###### Second
将Crack文件夹中的 R2016b/bin/glnxa64 四个文件，复制到 /usr/local/ATLAB/R2016b/bin/glnxa64 中

# Finally
下载 Software 中的 matlab support，在载入文件时输入 MATLAB 的 bin 文件夹所在文件夹
