# SqlMap-GUI
![预览](https://github.com/cx9208/SqlMap-GUI/raw/master/pic/Snipaste_2020-09-03_11-14-17.png)<br>
## 【注意】<br>
程序是易语言写的，360跟Defender肯定报毒，不认识我的就不要用了233<br>
## 【配置】<br>
一般直接丢进sqlmap目录里使用即可<br>
如果没有设置python环境变量的话修改sqlmapgui.ini内PythonPath项，指定python.exe位置<br>

## 【使用】<br>
粘贴raw请求到左边的框里，可以是burp拦截的请求、扫描器扫出的请求（最好把扫描器payload去掉）<br>
在右边挑选需要的参数，点击“一把梭”开始注入<br>
下方命令预览可以预览当前会执行的命令，双击预览可以复制命令<br>

小tip：<br>
>"注入-指定注入点" 中，可以在左边划选需要的注入点，点击+号添加<br>
>"注入-指定库，表，列" 中，可以在sqlmap跑出的结果里复制，点击+号添加<br>
>可以在一把梭上方编辑框添加自定义参数<br>
>"绕过-tamper列表" 为自动读取sqlmap目录内脚本，点击脚本自动读取脚本内介绍<br>
![预览](https://github.com/cx9208/SqlMap-GUI/raw/master/pic/Snipaste_2020-09-03_11-18-37.png)<br>
<br>
## 【更新日志】<br>
-> V1.6 20200903<br>
增加鼠标双击预览复制命令<br>
修复预览提示框bug<br>
增加找不到sqlmap的提示<br>
细节调整<br>
<br>
-> V1.5<br>
增加鼠标停留命令预览显示提示框<br>
增加“连接：直连数据库”<br>
细节调整<br>
<br>
-> V1.4<br>
增加“提取：不使用缓存”<br>
细节调整<br>
<br>
-> V1.3<br>
勾选“清空缓存(--purge)”后，点击一把梭会自动取消勾选<br>
增加“提取：数据库版本”<br>
增加“提取：主机名”<br>
<br>
-> V1.2<br>
细节调整<br>
增加“连接：使用HTTPS”<br>
<br>
-> V1.1<br>
增加sqlmapgui.ini，支持自定义py与sqlmap路径<br>
增加"控制：shell"<br>
增加"控制：读取文件"<br>
增加"控制：写入文件"<br>
<br>
-> V1.0<br>
初版诞生<br>
