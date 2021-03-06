### 泛化（*Generalization*）

【泛化关系】：是一种继承关系,它指定了子类如何特化父类的所有特征和行为

【箭头及指向】：带三角箭头的实线，箭头指向父类

![泛化](./img/Generalization.png)





### 实现（*Realization*）

【实现关系】：是一种类与接口的关系，表示类是接口所有特征和行为的实现

【箭头及指向】：带三角箭头的虚线，箭头指向接口

<img src="./img/实现.png" style="zoom:110%;" />





### 关联（*Association*)

【关联关系】：是一种拥有的关系,它使一个类知道另一个类的属性和方法；如：老师与学生，丈夫与妻子关联可以是双向的，也可以是单向的。双向的关联可以有两个箭头或者没有箭头，单向的关联有一个箭头。

【箭头及指向】：带普通箭头的实心线，指向被拥有者

![关联](./img/关联.png)





### 聚合（*Aggregation*）

【聚合关系】：是整体与部分的关系。如车和轮胎是整体和部分的关系
						   聚合关系是关联关系的一种，是强的关联关系；关联和聚合在语法上无法区分，必须考察具体的逻辑关系。

【箭头及指向】：带空心菱形的实心线，菱形指向整体，箭头指向部分

![聚合](./img/聚合.png)





### 组合(*Composition*)

【组合关系】：是整体与部分的关系，组合关系是关联关系的一种，是比聚合关系还要强的关系，它要求普通的聚合关系中代表整体的对象负责代表部分的对象的生命周期

【箭头及指向】：带实心菱形的实线，菱形指向整体，箭头指向部分

![组合](./img/组合.png)





### 依赖(*Dependency*)

【依赖关系】：是一种使用的关系,尽量不使用双向的互相依赖。

【箭头及指向】：带箭头的虚线，指向被使用者

![依赖](./img/依赖.png)





### 各种关系的强弱顺序

​		***泛化 = 实现 > 组合 > 聚合 > 关联 > 依赖***





### 类图关系

下面这张UML图，比较形象地展示了各种类图关系：



![类图关系](./img/关系图.gif)