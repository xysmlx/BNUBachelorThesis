==========
What's it?
==========
BnuThesis is a LaTeX thesis template package for 
Beijing Normal University in order to make it easy 
to write thesises for either bachelor, master or doctor.  
It's based on the LaTeX thesis template package 
THUThesis of Tsinghua University. 

BNUThesis 是北京师范大学学位论文 LaTeX 模板，支持硕士、博士论文格式。
由Gerry在清华大学论文Latex模板THUThesis的基础上，根据北京师范大学研究
生院的规定修改而来。模板结构与使用方法仍与原模板保持一致。具体操作请
参考清华大学模板说明文档thuthesis.pdf。


========
使用方法
========

1. 在CTeXLive中可使用LaTeX编译示例文档，支持eps、ps格式图像文件
   latex main
   bibtex main
   latex main
   latex main
   dvips main.dvi
   ps2pdf main.ps

   也可以使用 pdfLaTeX/dvipdfm(x)生成文档，支持jpg、png等通用图像格式。
   在CTeX套装或者TeXLive发行版下推荐使用 XeLaTeX 编译，但需要事先安装Adobe字体。

2. 编写论文时，注意保存所有文本文件为 UTF-8 编码格式，否则无法通过编译！
   参考示例文档：
     main.tex   主控文档
     data/      论文具体内容
     ref/       参考文献目录
     figures/   图片目录
   

========
如何升级
========
1. 下载新模板并解压缩
2. 将bnuthesis.cls, bnuthesis.cfg, bnubib.bst作相应替换即可。

==========
更新日志
==========
2014-03-12 更新为1.52。增加UTF8编码标记，CTeX 1.9.2所带WinEdt可直接打开编译。修正与TeXLive2013的兼容性问题。
2012-05-04 更新为1.51。修正注音字符输出问题。根据2012年封面格式更新模版。
2012-04-10 更新为1.5。默认不生成空白页。增加twoside选项，使双面打印时正反页面对齐。
           全面测试兼容性，支持 CTeX 2.9 和TeXLive2011。推荐使用XeLatex编译。
           打包PDFLatex编译所需的ccmap.sty文件。移除TeXLive2011中缺少的diagbox宏包。
           使用CTeX2.9.2的XeLateX编译时，宏包mathptmx出错，默认不启用。
2011-12-7  修正一处影响编译的命令错误，去掉hypernat宏包。
2011-4-8   更新为1.4。修正附录中的图表公式编号格式。规范要求附录按
	数字排列，于是采用 "附1.*"的格式。另外，之前参考文献样式文件
	会干扰缩进设定，影响参考文献页边距。现替换为清华的版本并重新定制。
	但由某些少见的参考文献类型生成的引用格式可能不够规范，比如报纸、专利。
2011-3-18  更新为1.3。增加学术成果部分；调整页边距，取消奇偶页差别，
	需要在装订时处理；增加修改目录小节缩进。
2011-1-11  更新为1.2。调整内部一致性，优化页面设置，修正了几处编译警告。
	移除模板中的eps图片，方便pdflatex编译。
2011-1-6   参考文献中作者超过3个时自动省略，添加 et al.
2010-12-7  修正参考文献格式。支持常见天文期刊缩写。
2010-12-2  更新为1.1。改善对XeLatex的支持，修正示例文件。
2010-11-28 发布1.0版

=========
遗留问题
=========
* 保密标签不知道具体格式，没有处理
