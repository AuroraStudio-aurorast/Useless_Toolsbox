# Useless Toolsbox

一个可以解压也可以让你血压飙升的没用工具箱！

## 编译需求

1. [易语言5.9](http://eyuyan.com)
2. 有Visual C++ 6.0或者Visual C++ 7.0的静态编译器（不支持更新的版本）
3. Windows Vista或更高版本

## 额外需求

1. [精易模块(必须)](http://ec.125.la)
2. UPX 3.95
3. [易语言助手](https://e.125.la/)

## 如何编译？

1. 安装好易语言，使用易语言打开“源码Codes”文件夹内的“UToolsbox.e”
2. 如果弹出重新定向模块窗口，请将每一项(除精易模块)定向到根目录“模块Mods”的对应文件
3. 打开易语言根目录，打开“tools”文件夹，按照源码中的“须知.txt”在“link.ini”末尾添加对应内容(该文件如果不存在，请使用易语言静态编译修复后再试)
4. 打开易语言，在顶部菜单单击“T.工具”，弹出的上下来菜单选择“O.系统配置”，在弹出的窗口选择“存根”，选择“使用用户自定义清单”，将源码中“清单.txt”的内容复制到编辑框内
5. 调试没有问题后，在顶部菜单选择“C.编译”，弹出的菜单选择“S.静态编译”，在选择保存路劲后即可编译
6. (可选)使用“工具Tools”内的“[套壳压缩]UPXShell3.95.exe”进行套壳压缩