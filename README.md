## ElectromagneticField

这是《电磁场与电磁波》课程的LaTeX笔记。

你可以直接下载PDF阅读，也可以自己动手构建，下面介绍一下我当时的步骤

1.下载texlive、vscode（可选）
2.选择XeLaTex编译ElectromagneticField.tex即可

可能出现的错误解决办法

1.error:Unable to load picture or PDF file 'Chapter0xx_0x.fig.pdf'
在构建时没有成功编译出pdf，故在texlive/vscode中依次将文件夹中.fig.tex/wls文件编译为pdf文件，并新建一个名为build的文件夹将其放入
2.error:The font "Noto Serif CJK SC" cannot be found
本地没有下载此字体，可以下载安装相应字体
若仍然没有解决可以在xNoteBook.cls中更改本地已有字体
