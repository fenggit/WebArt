
## HTML 中的布局方式

- 标准流
- 定位
- 浮动

### 标准流
[标准流](HTML%20-%20布局：标准流.html)

### 定位：position可选参数
- static：默认值，按照标准流布局
- relative：相对定位，通过left，top，right，bottom来改变元素的位置，可以相互覆盖的
- absolute：绝对定位，通过left，top，right，bottom设置位置，相对于窗口，
会脱离文档流，html高度就不包含这个元素高度了，如果有div包裹，则父类也需要设置，否则子div不起作用。
- fixed：固定定位，通过left，top，right，bottom设置位置，会脱离文档流,相对于窗口,永远在最上面，不随着页面滚动而移动，和absolute相似
- inherit：继承，继承父元素的定位属性

源代码演示：
- [relative](HTML%20-%20布局1：定位relative.html)
- [absolute](HTML%20-%20布局2：定位absolute.html)
- [absolute](HTML%20-%20布局2：定位absolute2.html) ==>如果有div包裹，则父类也需要设置，否则子div不起作用
 
- [fixed](HTML%20-%20布局3：定位fixed.html)==>常用登录弹窗/广告
- [fixed](HTML%20-%20布局3：定位fixed2.html) ==> 子div是fix则不受父div限制，不受制于父元素
 
 ### 浮动
 
 
 ### z-index
 可设置元素的叠加顺序，依赖定位属性，大的叠加小的，负数则被普通元素所覆盖
 