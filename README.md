#PYtorch+anoconda+jupyter
##这个教程在Windows和linux上都适用，并且不会出现什么显卡版本号不匹配的情况
####Anaconda 
    直接下载最新的anaconda然后conda create -n pytorch jupyter notebook cudnn(如果出bug，可以尝试先复制base环境然后再 create cudnn环境)
####Pytorch  
    自行查看适配版本 复制适配的cuda版本代码 这个代码先cmd+r打开命令行，然后activate pytorch 激活环境 输入代码即可（不会和原来的base环境冲突）
####jupyter
    anaconda里面下载即可，linux环境下如果打不开，可以ctrl+alt+t打开命令行，输入jupyter notebook 点击链接(windows 和 Linux都需要先激活环境)
