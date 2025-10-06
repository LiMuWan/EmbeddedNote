##### 1.【问答题】请写出三种野指针的成因

```
1. 指针声明了,没有初始化
2. 指针指向了数组越界的位置
3. 指针指向了已经释放的内存地址
```

##### 2.【问答题】 写出下列标识符各属于什么类型

```c
例子: int num = 10;       num变量的类型是: int
    
int *a1;		     int* 
double *a2[];	        double *[]
double (*a3)[];		    double(*)[]
int *a4(int, int);	  	 int *(int ,int)
int (*a5)(int, int);     int (*)(int,int)
```

##### 3. 【代码题】写出以下三种定义结构体类型变量的写法

```
方式1:struct Person{char *name,int age}; struct Person p1;
方式2:struct Person{char *name,int age}p1;
方式3:struct {char *name,int age}p1;
```

###### 4. 【代码题】写出以下三种定义枚举类型变量的写法

```
方式1:enum Color{red}; enum Color c1;
方式2:enum Color{red}c2;
方式3:enum {red}c3;
```

