# ISE+Hspice+Modelsim安装

## 安装ISE
\Xilinx.ISE.v9.1i.DVD-ZWT(ED2000.COM)(1)  setup

生成代码：在\Xilinx.ISE.v9.1i.DVD-ZWT(ED2000.COM)(1)\crack中打开keymaker

生成ISE V9i foundation edition的代码



## 安装 Hspice

\Hspice\Hspice 2009.09\hspice_vC-2009.09_Win_setup

\Hspice\Hspice 2009.09\sx_C-2009_09_windows

参考：\Hspice\Hspice 2009.09\crack



## 安装modelsim

如何安装Modelsim 64bit仿真软件，接下来就是一些基本步骤。

--------------------------------------------------

链接：https://pan.baidu.com/s/1ghkUxgpJhlxcDGWULJFCoQ 
提取码：czmu 
--来自百度网盘超级会员V4的分享

-----------------------------------------------------------------

1 首先关闭杀毒软件，安装MODELSIM 10.4SE，安装过程中弹出的界面选择“yes”，

**有一个地方一定要选择“NO”：安装完成后会弹出一个推荐安装 “ Hardware security Key Driver ”，点否，不然的话装了这个就无法完成破解。**

弹出是否重启电脑可以选择“no”

2 安装完成后复制MentorKG.exe和patch_dll.bat到Modelsim安装目录的win64目录下

3 将安装路径下win64\mgls64.dll 只读属性去掉 ，以管理员的权限（如果是win7,XP直接运行)运行patch_dll.bat，将生成的文件另存为LICENSE.TXT，保存文件到安装目录下。

（也可试**着运行MentorKG.exe，在关闭时生成license.txt**）

**注意：这里LICENSE.TXT会自己弹出来，保存即可**

 打开LICENSE.TXT，看里面的HOSTID值是否与自己电脑的以太网物理地址值是否一致。（WIN+R打开运行界面，输入cmd进入命令提示符界面，然后输入:ipconfig /all查询）例如： 

 <img src="https://img-blog.csdnimg.cn/20190304174620641.png" alt="img" style="zoom:80%;" />![img](https://img-blog.csdnimg.cn/20190304174658874.png)

修改完后把只读重新勾选上。

4 新建环境变量MGLS_LICENSE_FILE指向LICENSE.TXT，依次单击我的电脑－属 性 - 高级－环境变量 ， 添加变量名，系统变量和用户变量都添加。

 MODELSIM破解完成。

Modelsim 64bit安装成功。



<img src="C:\Users\shenlibo\AppData\Roaming\Typora\typora-user-images\image-20220417233335779.png" alt="image-20220417233335779" style="zoom:67%;" />










