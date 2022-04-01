# CSS

cascading style sheet：层叠式样式表，辅助布局

有两个重要概念：样式和布局；样式分为文字的样式和盒模型的样式；

从html4.0开始结构层和样式层进行了分离

# CSS常用属性：文字

css属性值的写法发生了变化，k:v;

文字三属性：color,font-size,font-family

### 颜色：color

属性值分为颜色的单词和色值（十六进制和rgba）

### 字号：font-size

根据浏览器的不同，有默认不同的字号大小，chrome和ie默认16px，chrome最小8px，ie1px（每个浏览器不一样）

### 字体：font-family

值必须以双引号包裹，多个使用逗号分开，按**顺序**加载

中文字体常用属性值：微软雅黑，宋体

英文字体常用属性值：Arial，Consolas

默认微软雅黑

# CSS常用属性：盒子

width，height，background-color

width，height常用都是以px为单位

background-color：background系列属性的一种

# CSS样式表:行内式，内嵌式，外链式，导入式

### 行内式样式表

直接把style属性写在标签上：\<p style="color: red;">让我康康！\</p>

引入位置：style属性中等号后面的引号内CSS样式，多个属性使用分号分隔

### 内嵌式样式表

位于head内部，title下面，一对style之中

### 外链式

也位于head内部，title下面，link标签

link就是通过herf引入外部文件

rel属性值如果是stylesheet就是样式表

### 导入式

位于head内部，title下面，一对style之中，但必须在style的最顶部，不好用

****权重**：行内式>内嵌式=外链式>导入式**
