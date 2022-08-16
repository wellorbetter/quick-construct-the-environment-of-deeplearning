# Pytorch+Anoconda+jupyter 快速构建深度学习环境

这个教程在Windows和linux上都适用，并且不会出现什么显卡版本号不匹配的情况，不会影响原环境的使用

## Anaconda 

```
直接下载最新的anaconda然后conda create -n pytorch jupyter notebook cudnn(如果出bug，可以尝试先复制base环境然后再 create cudnn环境) 
复制base环境:conda create -n base --clone yourname(这个是自己定义的名字)
```

## Pytorch  

    自行到官网查看适配版本 复制适配的cuda版本代码(一般情况下没问题，有问题重复上述步骤新建一个环境，试一下不同的版本) 这个代码先cmd+r打开命令行，然后activate pytorch(我的环境名字叫pytorch) 激活环境 输入代码即可（不会和原来的base环境冲突）

## jupyter

    anaconda里面下载即可，linux环境下如果打不开，可以ctrl+alt+t打开命令行，输入jupyter notebook 点击命令行弹出的链接(windows 和 Linux都需要先激活环境)
