# zyw_tool
可转债策略小工具使用指南  

#使用本工具，需要本地有python环境和.net6环境    
#如果使用的电脑上没有安装.net 6桌面应用运行时，则在双击打开StockBondFund.exe程序跳出提示界面点击*是*按钮即可跳转到下载页面，直接下载安装后即可完成.net6桌面运行时的安装  
#如果没有python环境，请自行百度下载anaconda3的windows版本进行安装，安装的时候选择自动添加环境变量    
#两者安装完毕后，打开cmd，分别输入dotnet命令和python或pip命令，如果正常显示则说明环境已安装好    

#使用本工具需要在本地搭建http服务，需要先安装akshare和aktools，在cmd执行以下两个命令进行安装     
pip install akshare --upgrade  
pip install aktools --upgrade  

#akshare版本更新频繁, 每次启动前先升级  
pip install akshare --upgrade       
pip install aktools --upgrade     

#akshare和aktools安装完毕后，需要启动本地http服务，在cmd执行如下命令启动，使用本工具期间cmd窗口不可关闭  
python -m aktools  

#如果aktools存在问题，代表该工具存在bug作者暂时未修复，我手动修复了一下，如果报错的话，就将resources目录里的api.py替换掉aktools/core/api.py    

#至此，环境配置完毕，可以打开StockBondFund.exe进行使用了    

