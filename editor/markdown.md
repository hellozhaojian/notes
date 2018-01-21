<center>MARKDOWN基本介绍</center>
<!-- TOC -->

- [1. math](#1-math)
- [2. graphic](#2-graphic)
- [3. 添加目录](#3-添加目录)
- [4. pdf](#4-pdf)
- [5. 添加图片](#5-添加图片)
- [6. 表格](#6-表格)

<!-- /TOC -->

# 1. math

* 在vscode中安装Markdown+Math
* 参考[LaTeX Math Symbols](https://oeis.org/wiki/List_of_LaTeX_mathematical_symbols)
1. 行间的公式

$$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}                 $$      (1)
2. 行内公式 $x=\frac{x}{y}$
3. 另外一个行内 $x^2+y^2=z \ngeq 4$


# 2. graphic
1. brew install graphviz
 
2. 基本的图形 


4. 时序图
```mermaid
graph TD;
A-->B;
A-->C;
B-->D;
C-->D;
```


# 3. 添加目录

1. 参考[Markdown TOC](https://www.jianshu.com/p/4721ddd27027)
2. 安装好插件后，Control + 左键 -> 选择 MarkDown TOC Insert/Update[ˆM T] 即可
3. 点击右侧的预览功能查查

# 4. pdf

1. Use the Markdown: Clip Markdown+Math to Html command or the key binding ('ctrl+K .'). 此时，html源码放置在剪贴板中，需要手动将数据粘贴到一个html文件，如tmp.html
2. brew install pandoc
3. 安装[maxtex](http://www.tug.org/mactex/mactex-download.html)
4. 查看mac支持的字体 system_profiler SPFontsDataType > /tmp/z.fond
5. pandoc tmp.html -o tmp.pdf --pdf-engine=xelatex -V CJKmainfont="STKaiti"

# 5. 添加图片
<img  src="/Users/alchemy_taotaox/Desktop/mygithub/profile/gru-image.jpg"/><br/>


# 6. 表格

|Header1 | Header2                | Header3|
|---------|-----------------------|--------|
|item 1  | 1. one 2. two 3. three | 你好|

#