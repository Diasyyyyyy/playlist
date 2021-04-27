# 控制台输入
### scanf和gets
输入一行字符串带空格的话，使用gets，scanf遇到空格会自动结束。
```javascript
 char s[105];  
 gets(s);
 printf("%s\n", s); 
```
### getchar和putchar
读入单个字符和输出单个字符，一般在scanf和gets中间使用getchar用于消除回车’\n’的影响
```c
 getchar(); 
```
# 控制台输出
### 输出进制转换
读入单个字符和输出单个字符，一般在scanf和gets中间使用getchar用于消除回车’\n’的影响
```c
 int a = 10;  
 printf("%x\n", a);//小写十六进制输出 答案a 
 printf("%X\n", a);//大写十六进制输出 答案A 
 printf("%o\n", a);//八进制输出  答案12  
```
### 输出增加前置0
```c
 int a = 5;  
 printf("%02d\n", a);//其中2代表宽度 不足的地方用0补充 
 //输出结果05  
 printf("%04d\n", a);  
 //输出结果0005  
```
### 输出保留小数
```c
 double a = 3.6;  
 printf("%.2lf\n", a);//2表示保留两位小数 
//输出结果3.60
```
有小数输出小数，没小数输出整数

# long long的使用
int范围-1e9到1e9，long long范围-1e18到1e18
```javascript
 long long x;  
 scanf("%lld", &x);  
 printf("%lld\n", x);
```
*（转载自知乎——n诺）*[link](https://zhuanlan.zhihu.com/p/93071794 "n诺").

<!-- Links -->
[下一章：oj错误提示](oj错误提示.md)



[README](README.md)