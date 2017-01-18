##Install
一条命令搞定 oh-my-zsh

###基于wget
```
sh -c "$(wget https://raw.githubusercontent.com/yw9381/oh-my-zsh_theme_line/master/install_zsh.sh -O -)"
```

###基于curl
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/yw9381/oh-my-zsh_theme_line/master/install_zsh.sh)"
```

##如何设置
修改家目录下.zshrc这个文件(```vim ~/.zshrc```)，将
```
ZSH_THEME="xxxx"
```

改为
```
ZSH_THEME="line"
```
即可
##信息说明
###第一行
**紫色字**部分表示的是当前的用户名及主机名  
**蓝色字**部分表示的是当前工作路径  
如果该目录是一个git管理的工作目录，则显示git信息(如图2)  
如果当前终端是一个以screen启动的虚拟终端，则显示出来screen信息(如图3)  
###第二行  
开始是用户输入光标  
末尾为当前时间
##相关截图
主界面（图1）  
![images/1.png](images/1.png)  
git信息查看（图2）  
![images/2.png](images/2.png)  
screen信息（图3）  
![images/3.png](images/3.png)


