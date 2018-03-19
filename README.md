# BNUBachelorThesis
Latex Template of BNU Bachelor Thesis based on BNUThesis_1.52.1

项目地址：https://github.com/xysmlx/BNUBachelorThesis

* **模板格式已通过图书馆审核**
* **由于教务处要求论文双页打印，所以Version 0.1 build 150512起，更改默认选项为双页打印版本，更改设置见main.tex的注释（如果是更新模板，则需改main.tex的第一行为\documentclass[bachelor,twoside]{bnuthesis}）**
* **如果有修改，只需覆盖掉bnuthesis.cls文件和bnuthesis.cfg文件即可变为最新版，论文正文不用变，建议交终稿前看一下更新（看时间戳即可）**
* **如果编译不过，试试安装字体（在References文件夹中），推荐使用PDFLaTeX（一次编译流程：PDFLaTeX+BiBTeX+PDFLaTeX+PDFLaTeX）或者XeLaTeX（CTeX和MACTeX均编译通过）**
* **注：新版本texlive的xeCJK包与模板有一些不兼容的问题，texlive 2012可编译通过，后续将尝试进行修复**

***
## Build History
***
### Version 0.1 build 150512
#### Update
1. 调整目录条目间距
2. 由于教务处要求论文双页打印，所以更改默认选项为双页打印版本，更改设置见main.tex的注释（如果是更新模板，则需改main.tex的第一行为\documentclass[bachelor,twoside]{bnuthesis}）
3. 添加Algorithm2e环境配置
4. 升级tabular环境配置（可以用L/R/C{x cm}控制列宽等）
5. et.al.

#### Pending to solve (DDL Before 5.15)
1. NULL

***
### Version 0.1 build 150506
#### Update
1. 重大Bug修复（图表编号每chapter清零）
2. 支持参考文献编号格式[1]
3. Bugs fixed
4. et.al.

#### Pending to solve (DDL Before 5.15)
1. 目录条目间距

***
### Version 0.1 build 150504
#### Update
1. 更改正文和附录图表公式格式（感谢指出问题所在）
2. Chapter标题上下间距（感谢指出问题所在）
3. et.al.

#### Pending to solve (DDL Before 5.15)
1. 目录条目间距
2. 支持参考文献编号格式[1]

***
### Version 0.1 build 150430
#### Update
1. 添加PDFLaTeX支持eps
2. 添加listing环境配置，可以写代码
3. Bugs fixed
4. et.al.

#### Pending to solve (DDL Before 5.15)
1. 目录条目间距
2. 标题间距
3. 支持参考文献编号格式[1]

***
### Version 0.1 beta
#### Update
1. 更新目录字体使之符合要求
2. 更新摘要格式
3. 更新参考文献格式
4. 更新页面设置
5. et.al.

#### Pending to solve
1. 目录条目间距
2. 标题间距

***
### Version 0.1 alpha
#### Update
1. 完成大部分更改使之符合要求

#### Pending To Solve
1. 目录格式
2. 页面上下边距

***
## References
1. 基于《北师大学位论文Latex模板》(BNUThesis_1.52.1)：http://gerry.lamost.org/blog/?p=811 制作
2. 《毕业论文写作规范（修订）》（师教文[2007]186 号）：http://jwc.bnu.edu.cn/gzzd/sjjxl/32843.htm
3. 北京师范大学图书馆Word版学士模板2015年版本：http://epaper2.lib.bnu.edu.cn/tpi_1/thesis/degree/papervedio_files/download/xueshimoban.dot
4. 北京师范大学信息科学与技术学院Word版写作模板
