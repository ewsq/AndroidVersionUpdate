# AndroidVersionUpdate
主要根据安卓app的版本号对比，来检测需要更新的版本，通过网络下载之后，自动安装完成更新。主要过程：1.检测当前版本的信息2.从服务器获取版本号（版本号存在于xml文件中）并与当前检测到的版本进行匹配，如果不匹配，提示用户进行升级，如果匹配则进入程序主界面。（demo中假设需要更新）  * 3.当提示用户进行版本升级时，如果用户点击了“更新”，系统将自动从服务器上下载安装包并进行自动升级，如果点击取消将进入程序主界面。
