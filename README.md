# imgLayout

Jquery图片瀑布流布局
1. 是用的jquery写的哦，其中要计算其包括margin在内的图片宽（需设置.outerWidth(true)）;
因为我之前忘记了加true，后面效果都变了。
2. 获取一个数组中的最小值 -> Math.min.apply(null, arr);  用apply可将数组作为一个参数传入。
3. 获取数组某一个值的索引值 -> $.inArray(val, arr);

效果图：
![image](https://github.com/enaat/imgLayout/blob/master/img/demoShow.png)
