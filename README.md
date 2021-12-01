<!-- Author : Kaleidoscope-->
<!-- Program Email: Kaleidoscope798@163.com -->

# SHUbeamer介绍

**SHUbeamer**是为了帮助上海大学师生撰写演示文稿而编写的LaTex Beamer模版文件, 模板的组成文件如下: 

```latex
  |- figures	%图片存储文件夹
    |- SHU-blue.pdf
  |- logo	%模版中使用的背景、logo等文件
    |- background.pdf
    |- SHDX-tight-white.pdf
    |- SHU-white.pdf
  |- style	
    |- gbt7714-2005.bst	%符合 GB/T 7714-2005 规范的 BibTeX 样式文件
    |- macros.tex	%常用的
    |- shubeamer.sty	%主题宏包、说明文档以及主题驱动文件的混排文件
  |- CMU Serif.ttf	%模版使用的CMU Serif字体
  |- main.pdf	%main.tex所排版出的PDF文件
  |- main.tex	%主题测试文档
  |- README.md
  |- reference.bib	%参考文献
```

模版主题颜色默认使用来自上大官网边栏的深蓝色(RGB={27,70,123}), 当然你也可以模版文件 `shubeamer.sty` 中将该行注释掉, 再将注释为 `SHU blue` 的一行前面的`%`去掉, 此时主题颜色将变为上大蓝. 

# 问题反馈

[联系邮箱](Kaleidoscope798@163.com): Kaleidoscope798@163.com

# 致谢

作为本人为了对付上海大学答辩的第一个自己修改制作的beamer, 本模版在缝合方面可谓是无所不用其极: 

> - 模版的主体改自浙大的[corenel](https://github.com/corenel)/**[zju-beamer-theme](https://github.com/corenel/zju-beamer-theme)**; 
> - 种种示例来自清华的[YangLaTeX](https://github.com/YangLaTeX)/**[thubeamer](https://github.com/YangLaTeX/thubeamer)**; 
> - 符合 GB/T 7714-2005 规范的 BibTeX 样式文件来自南大的[Haixing-Hu](https://github.com/Haixing-Hu)/**[nju-thesis](https://github.com/Haixing-Hu/nju-thesis)**; 
> - 上海大学 logo 的高清矢量图则来自本校同学的[ahhylau](https://github.com/ahhylau)/**[shuthesis](https://github.com/ahhylau/shuthesis)**. 

对以上的GitHub项目, 本人表示深深的感谢🙏! 