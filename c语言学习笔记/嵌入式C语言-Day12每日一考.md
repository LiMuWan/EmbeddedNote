##### 1. 【简答题】非静态局部变量、全局变量、malloc()动态分配的内存分别存储在内存的什么区域。

```
非静态局部变量：栈区
全局变量: 全局静态区
malloc(): 栈区和堆区
```

##### 2. 【简答题】至少写出三个用于动态内存分配的 C 语言函数

```
malloc()函数
calloc()函数
realloc()函数
free()函数
```

##### 3. 【编码题】请按照如下要求编写代码

* 声明一个结构体，有成员 `char *` 类型的name 和 `int` 类型的 age
* 使用 typedef 为结构体取别名为 Person
* 使用结构体别名，声明结构体变量 per
* 创建结构体指针 ptr, 指向结构体变量 per
* 通过结构体指针 ptr，设置成员 name 的值为 "xiaowang", 成员 age 的值为 501

> **温馨提示：** 声明结构体所用的关键字是 struct。

```;
typedef struct{
 char *name;
 int age;
}Person;

Person per;
Person *ptr = &per;
ptr->name="xiaowang";
ptr->age=501;
```

