1.span是行内元素
2.clue提示
3.input里面设置min max属性可限制数值大小
4.lable里的for属性要和其对应的input里的的id属性相对应
5.type="radio"的input中checked属性是默认选择该单选按钮的意思
6.input里的name属性：
7.name 属性用于对提交到服务器后的表单数据进行标识，或者在客户端通过 JavaScript 引用表单数据。只有设置了 name 属性的表单元素才能在提交表单时传递它们的值。
8.em相对于父元素，rem相对于根元素。
9.::before在每个该元素的内容之前插入内容，并设置插入内容的样式：
10.font-weight设置字体粗细
11.var()函数用于插入 CSS 变量的值。eg. `color: var(--color-white);`
12.:root可用于声明全局CSS 变量：
13.css中*选取所有元素
14.box-sizing 属性定义了应该如何计算一个元素的总宽度和总高度。
在 CSS 盒子模型的默认定义里，你对一个元素所设置的 width 与 height 只会应用到这个元素的内容区。如果这个元素有任何的 border 或 padding ，绘制到屏幕上时的盒子宽度和高度会加上设置的边框和内边距值。这意味着当你调整一个元素的宽度和高度时需要时刻注意到这个元素的边框和内边距。当我们实现响应式布局时，这个特点尤其烦人。
box-sizing 属性可以被用来调整这些表现：
content-box  是默认值。如果你设置一个元素的宽为 100px，那么这个元素的内容区会有 100px 宽，并且任何边框和内边距的宽度都会被增加到最后绘制出来的元素宽度中。
border-box 告诉浏览器：你想要设置的边框和内边距的值是包含在 width 内的。也就是说，如果你将一个元素的 width 设为 100px，那么这 100px 会包含它的 border 和 padding，内容区的实际宽度是 width 减去 (border + padding) 的值。大多数情况下，这使得我们更容易地设定一个元素的宽高。
15.input,select元素中required表示需要输入