### 判断

08是正确的整型常量。    False

表达式 ~(~2<<1)的值是5。    True

表达式 (z=0, (x=2)||(z=1),z) 的值是1。  False

运算符“+”不能作为单目运算符。   False

### 选择

下面的程序段输出是（ ）。   D
```C
int k=11;
printf("k=%d,k=%o,k=%x\n",k,k,k);

A.k=11,k=12,k=11
B.k=11,k=13,k=13
C.k=11,k=013;k=0xb
D.k=11,k=13,k=b
```

下面的程序段输出是（ ）。   B
```C
short int a;
int b = 65536;
a = b;
printf("%d\n", a);

A.65536
B.0
C.-1
D.1
```

阅读以下程序段，如果从键盘上输入1234567<回车>，则程序的运行结果是（ ）。    D
```C
int i,j;
scanf("%3d%2d",&i,&j);
printf("i = %d, j = %d\n",i,j);

A.i = 123, j = 4567
B.i = 1234, j = 567
C.i = 1, j = 2
D.i = 123, j = 45
```

阅读以下程序段，如果从键盘上输入abc<回车>，则程序的运行结果是（ ）。A
```C
char ch;
scanf("%3c",&ch);
printf("%c",ch);

A.a
B.b
C.c
D.语法出错
```

已知字符'A'的ASCII码是65，分别对应八进制数101和十六进制数41，以下（ ）不能正确表示字符'A'。 D
```C
A.'A'
B.'\101'
C.'\x41'
D.'\0x41'
```

设以下变量均为int类型，表达式的值不为 9 的是（）。  C
```C
A.(x = y = 8, x+y, x+1)
B.(x = y = 8, x+y, y+1)
C.(x = 8, x+1, y = 8, x+y)
D.(y = 8, y+1, x = y, x+1)
```

运算符（ ）的优先级最高。   A
```C
A.[ ]
B.+=
C.? :
D.++
```

执行下面程序中的输出语句后，输出结果是（ ）。   B
```C
int a;
printf("%d\n",(a=3*5,a*4,a+5));

A.65
B.20
C.15
D.10
```

### 填空

写出以下程序的运行结果。请注意，直接填数字或者字符，前、后和中间不要加空格。
```C
#include <stdio.h>
int main(void)
{
    int c1 = 0, c2 = 0;
    char ch;                      
    while((ch = getchar()) != '#'){
        switch(ch){
              case 'a':
              case 'h': c1++;
              default: c2++;
        }
    }
    printf("c1=%d,c2=%d\n", c1, c2);   /* 中间、前、后都没有空格 */
    return 0;
}
```
输入china#，输出（）    c1=2,c2=5

