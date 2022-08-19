# zyw_tool
可转债策略小工具  

#使用前先安装akshare aktools     
pip install akshare --upgrade  
pip install aktools --upgrade  

#如果上方pip命令执行不了，说明需要安装anaconda3或者python3(3.7以上版本)  
#直接搜索安装方法即可  

#akshare版本更新频繁, 每次启动前先升级  
pip install akshare --upgrade -i https://pypi.org/simple  
pip install aktools --upgrade -i https://pypi.org/simple  

#启动程序前，先启动本地http服务  
python -m aktools  

#目前 aktools存在问题，作者暂时未修复，我手动修复了一下，如果报错的话，就讲resources目录里的api.py替换掉aktools/core/api.py    

#如果使用的电脑上没有安装.net 6桌面应用运行时，则在程序跳出提示界面点击*是*按钮即可跳转到下载页面，直接下载安装后即可正常使用本工具  