# math

* 参考[markdown中插入数学公式](http://blog.csdn.net/xiahouzuoxin/article/details/26478179)
* 详细介绍MathJax

```
    在下面的标签中插入数学公式
    <script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>
```

<script type="text/x-mathjax-config">
MathJax.Hub.Config({
 tex2jax: {inlineMath: [['$','$'], ['\(','\)']]}
});
</script>
<script type="text/javascript"
  src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>

$$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$$
\\(x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}\\)
