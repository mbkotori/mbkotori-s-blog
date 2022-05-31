# 在线LaTeX公式编辑器：
<https://www.latexlive.com/>
![](http://ys-d.ys168.com/614621451/813403421/mndqtlm45362T7LHHO59a/latex%E7%BC%96%E8%BE%91%E5%99%A8.PNG)
## 写法如下：
```
$$O^{i} =x^{i}W+b$$
```
 这个latex方法似乎不是markdown自带的,如果要实现latex似乎需要使用到js渲染(不知道说的对不对),总之按gridea看来得在主题文件中包含,本人还没有修改主题的能力,只能将手头的主题重新尝试了下选定了一个

之后按这个顺序做了下测试,看看具体写作方法:(怪捞的)
```
看看$$O^{i} =x^{i}W+b$$
看看$O^{i} =x^{i}W+b$
$$O^{i} =x^{i}W+b$$
$O^{i} =x^{i}W+b$
```
在gridea的本地渲染是这样的:
![](http://ys-d.ys168.com/614621451/813403422/mndqtlm45362T7LHHO694/latex%E6%B5%8B%E8%AF%95.PNG)
下面是为了测试看主题带的渲染和gridea本地是否相同写下的四行:

看看$$O^{i} =x^{i}W+b$$
看看$O^{i} =x^{i}W+b$
$$O^{i} =x^{i}W+b$$
$O^{i} =x^{i}W+b$

由此看出,双美元符号$$是行间公式,单美元符号$是行内公式
另一个有趣的是在符号之间输入\时是会有latex关键字提示的,很方便

# 另一种方法,利用知乎渲染的api进行公式书写
不过这样似乎就变成html语句了,且输出公式时图片一张,不方便行内书写和格式调整
书写方法和展示结果如下:
```
<img src="https://www.zhihu.com/equation?tex=O^{i} =x^{i}W+b" />
```
<img src="https://www.zhihu.com/equation?tex=O^{i} =x^{i}W+b" />