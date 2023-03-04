### 重拾前端day04作业

#### 一、说明text-align实现居中的条件

text-align居中是针对行内级元素(inline-level)，比如图片img、文本等

对于块级元素，想要用这个属性进行居中，可以通过display：inline-block**将块级元素转换成行内块元素**



#### 二、line-height为什么可以实现文字居中？

line-height表示一行文字的高度，也表示两条两行文字基线之间的间距

当line-height等于height，则可以使这行文本在此div内进行垂直居中

因为：行高 - 文字高度 = 行距，行距进行上下平分，就实现文本垂直居中



#### 三、选择器

- 通用选择器 *{}
- 简单选择器
  - 类选择器     .box{}
  - id选择器      #box{}
  - 元素选择器  div{}
- 后代选择器
  - 拥有某一个属性 [attr]{}
  - 属性=某一个值 [attr=val]{}
  - 属性包含某一个值 [attr^=val]
- 兄弟选择器
  - 相邻兄弟选择器,用+连接   .one+div {}
  - 普遍兄弟选择器,用~连接     .one~div {}
- 选择器组
  - 交集选择器 div.box{}
  - 并集选择器 div, p, h1{}
- 伪类选择器
  - :link
  - :visited
  - :focus
  - :hover
  - :active