# Onekey-rename-
再不用一个文件一个文件的命名，一键重命名批处理工具可以让你快速批量命名你的文件
### 博客： 行走的代码 | Tespera的博客 | 林深时见鹿，海蓝时见鲸，梦醒时见你。(www.tespera.com) 



### 使用方法：

1、下载 <b>一键重命名.bat</b>。

2、将其放在需要命名的文件所在的文件夹。

3、用记事本打开 <b>一键重命名.bat </b>文件。

4、修改 <code>  for  /f "delims=" %%x in ('dir /b *.txt') do </code>  这一行代码的 <code> *.txt </code> 为你自己文件的扩展名，如 <code> *.mp3 </code> 

5、修改 <code> rename "%%x" "文件名 - !sum! .txt" </code> 该行代码的 “文件名” 为你自己想要命名的文件名，<code> *.txt </code> 修改为你自己文件的扩展名，如：<code> *.mp3 </code> 

6、Ctrl + S 保存，双击 <b> 一键重命名.bat </b> 即可。

7、该文件夹下的所有文件将全部被格式化重命名，所见即所得。

