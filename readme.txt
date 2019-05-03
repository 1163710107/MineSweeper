环境配置
OpenGL环境配置：
opengl的安装需要virsual c++的环境，首先下载安装Visual C++ Building Tools
安装成功后，从开始菜单打开Visual C++ Native Build Tools Command Prompt
使用命令行pip install PyOpenGL安装PyOpenGL

glut环境配置
下载glut库
将得到的glut.lib和glut32.lib这两个静态函数库复制到文件目录的lib文件夹下 C:\Program Files (x86)\Microsoft Visual Studio 12.0\VC\lib
将glut.dll，glut32.dll这两个动态库文件放到操作系统目录下面的 C:\Windows\system32 文件夹内（32位系统）或 ?C:\Windows\SysWOW64（64位系统）为了兼容性考虑，最好在这两个目录下都复制相应的文件。
将解压得到的头文件glut.h复制到目录如下目录下： C:\Program Files (x86)\Microsoft Visual Studio 12.0\VC\include\GL

注意：游戏过程中不能缩放游戏窗口，否则会产生错误