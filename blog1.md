掌握Linux内核使用对程序员来说是必备的技能，下面就简单介绍一下常用的Linux命令行使用教程，介绍的时候把尽量举例，方便理解。

![Paste_Image.png](http://upload-images.jianshu.io/upload_images/5976401-7878d07ffea8b9bd.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

Linux命令格式及使用

Linux命令的格式为“命令”+“选项”+“参数”，命令和参数是必备的，有些命令没有选项。比方说新建名为“file.docx”的文件，对应的Linux命令为“touch file.docx”，这里就没有选项。使用Linux命令在终端进行，类似于windows下的cmd和powershell终端，打开之后直接键入就可以操作。

![Paste_Image.png](http://upload-images.jianshu.io/upload_images/5976401-426afdb64f44e817.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

创建文件

在Linux中，创建一个新文件夹可以使用“mkdir “文件夹名称” ”来实现。比方说，在当前目录下创建一个叫做“new”的文件夹。对应的终端命令应该是“mkdir new”中间有空格哈。

![Paste_Image.png](http://upload-images.jianshu.io/upload_images/5976401-c9bdf243f9e483fc.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

切换位置

跟cmd类似， Linux切换路径的命令也是“cd”。

切换到C盘              cd c:/

切换到上级目录      cd ..

返回之前的目录      cd -

这几个cd之后都是有空格的哦。

![Paste_Image.png](http://upload-images.jianshu.io/upload_images/5976401-0532124e1ad1834b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

删除文件

删除命令在Linux当中也比较常见，不过跟windows不同，Linux是没有回收站的，删除有风险，尤其是强制删除。

删除new文件夹                              rm -f new

强制删除new文件夹下所有内容      rm -rf new

一般删除用rm -f就可以了，rm -rf是强制删除，慎用。

![Paste_Image.png](http://upload-images.jianshu.io/upload_images/5976401-8c5e826edee88173.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

编辑文件

编辑文件使用的是vi +文件名称来进行。比方说在当前目录下新建一个file.txt的文件夹，然后通过vi进行编辑，那么完整的命令行就是。

touch file.txt

vi file.txt

进入之后编辑，需要保存退出的话，可以按ESC，然后键入“:wq”即可。
