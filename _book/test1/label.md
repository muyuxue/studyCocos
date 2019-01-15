# 字体资源

组件 

​	Label

​		显示方式：可以用 系统字体，动态字体，艺术字资源LabelAtlas 和 位图字体 推荐用 http://www.angelcode.com/products/bmfont/。

​		<font color=#A52A2A  >艺术字资源不推荐使用，因为创建的时候要计算大小，并且生成字体要按照ASCII(应该是这个编码格式)，限制性高</font>

​	性能注意：如果是系统字体和TTF字体，仍然会打算批次，增加drawcall,如果是做prefab或者scrollView组件或者场景布局，仍然要注意sprite和label的排版位置，如果是位图字体，只要打了自动图集，就会在这个图集下只有1的drawcall

​	富文本RichText   一般用在跑马灯上使用较少