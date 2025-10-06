##### 1 【问答题】 break 和 continue 有什么区别

```
break是一个关键字,可以用来跳出switch-case语句,同时可以在while/do-while/for循环中使用,可以跳出所在的循环
continue是一个关键字,可以在while/do-while/for循环中使用,用来结束本次循环,继续下一次循环
都是关键字,break是跳出当前循环,continue是结束本次循环,继续下一次循环
```



##### 2 【问答题】 while 和 do while 有什么区别

```
while循环需要先判断循环条件是否成立,再决定是否执行循环体
do-while循环先执行一次循环体,然后再判断循环条件是否成立
while是先判断,后执行循环体,do-while是先执行循环体,后判断
while有可能一次循环体都不执行,do-while是至少执行一次循环体
```



##### 3.【代码题】请写出下面程序的运行结果

```c
int sum = 0;
for (int i = 1; i < 5; i++)
{
    if (i == 4)
        continue;
    sum += i;   // 
}
printf("%d", sum);   
// 结果是6
```

##### 4.【代码题】以下代码共输出多少个”尚硅谷“

```c
for (int i = 1; i <= 3; i++)
{
    for (int j = 1; j <= i; j++)
        printf("尚硅谷 "); 
}
// 输出6次
```

##### 5. 【编码题】使用 for/while/do-while 实现一个死循环

```
while(1){}
do{}while(1);
for(;;)
```











