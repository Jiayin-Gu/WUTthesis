# WUTthesis

WUTthesis 是一个针对武汉理工大学研究生学位论文的 LaTeX 模板，该新模板是根据《武汉理工大学博士、硕士学位论文撰写、印刷格式的统一要求（2009 年 7 月修订）》制作的。

## 特性
1 该模板是在 ctexbook 文类的基础上制作而成，因此 CTeX 宏集中的一切设置命令都可以使用。

2 该模板遵循简单性原则，没有做过多的封装，尽量将一些格式设置放在主文件的导言区。过多的封装会隐藏模板设计细节，从而影响用户对模板的理解。（这里鼓励用户在遵循学校统一格式要求和充分理解设计细节的情况下，根据自己的需求对模板进行修改。）

3 该模板的结构必须和学位论文的结构保持一致，从而可以使用户能快速且直观地理解模板的结构。

4 该模板使用 biblatex 宏包功能进行参考文献相关的处理，并使用 gb7714-2015 样式，该样式由宏包 biblatex-gb7714-2015 提供，是胡振震根据《GB/T 7714-2015 信息与文献参考文献著录规则》的要求开发而成。

5 该模板增加了日文、韩文、俄文的一些字体定义，用户可以根据需求使用。

## 使用

使用 [TeX Live](http://tug.org/texlive/) 套装，该套装适用 Unix-like/Microsoft Windows/macOS 。

使用 xelatex 编译方式。

使用 biber 后台程序进行参考文献处理。


## WUTthesis 制作者
顾加银，江苏省盐城市人，武汉理工大学理学院，2019 年博士研究生毕业，电子邮箱：gujiayin1234@163.com 。


## 许可证
[GNU GPLv3](https://choosealicense.com/licenses/gpl-3.0/)



## WUTthesis 日志
2019 年 3 月，作者本人使用 LaTeX 排版博士学位论文，在此过程中依据学校规定的格式要求进行了大量的 LaTeX 格式设置。在学校网上系统提交学位论文时有被要求提供 doc 格式文档，而作者本人将使用 LaTeX 排版生成的 pdf 格式文档后缀名改为 doc 后提交，从而骗过了系统。

2020 年 2 月，作者本人根据去年在使用 LaTeX 排版博士学位论文时进行大量格式设置制作了《武汉理工大学研究生学位论文 LaTeX 模板：WUTthesis》，在 Linux/Microsoft Windiows 上基于 TeX Live 套装测试成功，同时将该模板发布到 GitHub 网站上。由于受 COVID-19 疫情的影响，几乎所有高校都推迟了春季开学时间，进而会耽误大量处于毕业季的研究生的正常毕业进度，这里希望 WUTthesis 能够在毕业生撰写学位论文过程中发挥点作用，至少减少一些因为调格式而产生的时间上的浪费。



