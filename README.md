# 重庆邮电大学本科毕业（论文）LaTeX版本使用手册
此文档用于重庆邮电大学本科毕业设计（论文）的 LaTeX 模板使用，LaTeX 是一种基于Tex的排版系统，LaTeX版本与Word版本在格式要求上完全相同。
## 一、LaTeX 环境配置
推荐使用 texStudio 作为 LaTeX 的编辑器，安装了 texLive 才能使用 texStudio 编辑器，所以需要下载 texLive（必选）和 texStudio（可选）。

[本地编辑软件下载链接](https://blog.csdn.net/weixin_47581344/article/details/124356086)

[Overleaf在线环境链接](https://cn.overleaf.com)

[LaTeX 常用语法教程参考链接](https://blog.csdn.net/tianzong2019/article/details/106521432)

[LaTeX 教学视频入门参考链接](https://www.bilibili.com/video/av6564090)

[LaTex 相关规范](https://github.com/Haixing-Hu)

[在线latex公式编辑器](https://www.latexlive.com)

[表格生成器](https://www.tablesgenerator.com)

## 二、模板文件夹结构说明
根目录下的 main.tex 文件负责整个工程的结构，其余的可编辑源文件在文件夹 chapters下面，正文每章一个tex文件，除正文外每页一个tex文件。文件夹中的main.tex使用上面
安装好的texStudio打开（也可以使用 texLive 自带的 Texworks 编辑器打开）/也可将下载的压缩文件上传到Overleaf网站上。
![image](https://user-images.githubusercontent.com/55845745/180152693-486f6767-c939-484c-961d-723fb40a9370.png)

## 三、使用说明
latex_settings：设置工程中所需要的格式，即 Latex 中的引言区的设置。页眉页脚字号等的代码全部在latex_setting/custom-chinese.tex文件中，一般不需要进行改动，只需要做一些章节文字的填充，就能生成带格式的论文。

论文填写，要填写的论文章节都在 chapters 文件夹下。

❖ 填写中文封面页；chapters/pagetitle-chinese.tex

❖ 填写原创性声明页；chapters/original.tex

❖ 填写中文摘要页；chapters/abs-chinese.tex

❖ 填写英文摘要页；chapters/abs-english.tex

❖ 填写文章的各个章节内容；各个章节对应在 chapters/chapter0X.tex 中，X代表章节的数字。需要注意的是写文章主体时，用到的插图放在images文件夹下。

❖ 填写参考文献；chapters/ref.tex

❖ 此模板的参考文献模板是GB/T 7714-2005.bst，所有使用的参考文献都在reference/ref.bib文件内部，参考文献的格式是GB/T 7714-2005。根据你自己的参考文献的类型，填充必要的参考目录信息，比如author，title等。

❖ 填写致谢；chapters/thanks.tex

❖ 填写附录；chapters/appden.tex

## 四、导出全文
本地环境下导出正文全文或者测试结果见 main.pdf 文件。在线环境下直接下载PDF即可。
## 五、注意事项
修正日期为2022年7月20日，欢迎后来者修订并上传新版。欢迎交流使用。

使用者的权利包括且不限于：复制、修改源代码代个人学习。

如果使用遇到问题：可提Issue后邮件联系。
联 系 人：教务处实践教学管理科 李 茜 62487849

技术支持：计算机科学与技术学院 卢星宇 luxy@cqupt.edu.cn

仓库管理员：JQBY　2311323627@qq.com
## 贡献者
编者：教务处，李茜，等；计算机学院，卢星宇，刘媛媛，等。

特别感谢2022届先进制造工程学院，张治勇对初版Latex模板的大量贡献。

仓库管理员在原有基础上进行模板优化。
