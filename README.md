# pane-fixer-centos
亲测在Centos7.5环境下有效  
csdn博客：  

如何修复  
----------
`git clone https://github.com/JamesHoi/pane-fixer-centos.git`  
`cd electron-ssr-0.2.6-autoinstall`  
`chmod +x install.sh`  
`./install.sh`  
将以上命令输入到centos终端即可  

题外话（个人笔记）
--------
### 如何查看当前系统所使用语言包？  
`locale`  
  
### 如何将系统语言改为中文？  
`yum install kde-l10n-Chinese`  
`vim /etc/sysconfig/i18n`  
将文件内容修改为 `LANG="zh_CN.UTF-8"`  
`source /etc/sysconfig/i18n`  
  
### 如何将系统语言改为英文？  
`vim /etc/sysconfig/i18n`  
将文件内容修改为 `LANG="en_US.UTF-8"`  
`source /etc/sysconfig/i18n`  


