【说明】
    这里提供了一些用Delphi写的Sciter示例，有些示例使用标准Delphi窗口、有些使用Delphi的无边框窗口，而有些是使用图层窗口(即该窗口是透明的，但是图层窗口上不能放有句柄的子控件)。这些示例演示了Sciter的以下特征：

1.如何显示一个Sciter窗口；
2.如何操作Sciter窗口中HTML文档中的各个DOM元素；
3.如何给某个元素绑定时间行为；
4.

/360 ——
    一个仿360新版界面的Demo，该界面从一个Delphi窗口TSciterForm继承下来的，是一个图层窗口。
   
/d360_2 ——
    一个仿360旧版界面的Demo，该界面从一个Delphi窗口TSciterForm继承下来的，是一个图层窗口。
   
/d360_3 ——
    一个仿360旧版界面的Demo，嵌入了一个Delphi子窗口，该界面从一个Delphi窗口TSciterForm继承下来的，因有子窗口的界面不能为图层窗口，所以这个程序的主界面不是图层窗口。

/d360_4 ——
    一个仿360旧版界面的Demo，绑定了一个Delphi子窗口，这个子窗口没有嵌入父窗口，而是跟着父窗口一起移动，所以这个子窗口的父窗口可以是图层窗口。