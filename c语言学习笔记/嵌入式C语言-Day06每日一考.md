##### 1. 【代码题】请写出下面程序的运行结果

```c
int nums[] = {10,20,30,40};
char msg[] = "Hello";	// 

printf("%zu \n", sizeof nums);	// 16
printf("%zu \n", sizeof nums / sizeof nums[0]);	  //  4
printf("%zu \n", sizeof nums / sizeof (int));	 // 4
printf("%zu \n", sizeof msg);		// 6
```

##### 2. 【代码题】写出下面程序运行结果

```c
int arr[3][2] = {
    {10,20},
    {30,40},
    {50,60}
};
printf("%d", arr[1][1] + arr[2][0]);     // 90
```

##### 3 【问答题】写出下面程序运行结果

```c
int main(){
	char chs1[5]= {'a','b','c','d','\0'};
	char chs2[] ={'a','b'};
	printf("%s",chs2); // ababcd
	return 0;
}
```

##### 4.【代码题】写出 int nums\[3\]\[5\]这个二维数组的行和列的计算表达式

```c
int rows = sizeof(nums)/sizeof(nums[0]); // 行
int cols = sizeof(nums[0])/sizeof(nums[0][0]); // 列
int cols = sizeof(nums[0])/sizeof(int); // 列
```



##### 5.【编码题】有数组 `double nums[4] = {12.0, 65.2, 11.8, 13.3};`，计算所有元素的和,请写代码。

```c
double sum = 0; // 求和
int len = sizeof(nums)/sizeof(double); // 长度
for(int i=0;i<len;i++){
    sum+=nums[i];
}
printf("和为:%d\n",sum);
```



##### 6. 【编码题】请写出定义字符数组的写法(3种即可)

```
char chs1[5]={'a','b','c','d','\0'};
char chs2[5]={'a','b','c','d'};
char chs3[]={'a','b','c'};
char chs4[3]={'a','b','c'};
char chs5[]={"abc"};
char chs6[]="abc";
```










