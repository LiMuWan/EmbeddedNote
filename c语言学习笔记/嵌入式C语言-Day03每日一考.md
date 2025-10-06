##### 1. 请写出下面代码的输出结果

```c
printf("%zu", sizeof(12.5)); 			// 8
printf("%zu", sizeof 20);				// 4
printf("%zu", sizeof('a' + 'b'));		// 4
printf("%zu", sizeof(3.0f + 18LL)); 	// 4
```

##### 2. 写出下面代码执行后输出结果的数据类型

```c
double d=23.45;
float f= 10.7f;
int result = (int)(d+f);
结果的类型是int
```

##### 3..写出下面程序的输出结果

```c
char ch='A';
printf("%d", sizeof(ch));	
结果: 1
```

##### 4.【问答题】写出下面的字面量值,默认是什么类型 	

```
数字:  100   int
数字:  58.0f   float
```

##### 5.【问答题】下列数据类型的存储大小是多少字节

​	 **long long、short、int、float、double**

结果: 8 2 4 4 8