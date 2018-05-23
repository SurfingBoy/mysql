# 常用函数

### 字符串函数

| 函数 | 功能 |
| :- | :- |
| CONCAT(S1,S2,..Sn) | 连接S1,S2,...Sn为一个字符串 |
| INSERT(str,x,y,instr) | 将字符串str从第x位位置开始,y个字符长的子串替换为字符串instr |
| LOWER(str) | 将字符串中所有字符变为小写 |
| UPPER(str) | 将字符串中所有字符变为大写 |
| LEFT(str,x) | 返回字符串str最左边的x个字符 |
| RIGHT(str,x) | 返回字符串str最右边的x个字符 |
| LPAD(str,n,pad) | 用字符串pad对str最左边进行填充,直到长度为n个字符长度 |
| RPAD(str,n,pad) | 用字符串pad对str最右边进行填充,直到长度为n个字符长度 |
| LTRIM(str) | 去掉字符串str左侧的空格 |
| RTRIM(str) | 去掉字符串str行尾的空格 |
| TRIM(str) | 去掉字符串行尾和行头的空格 |
| REPEAT(str,x) | 返回str重复x次的结果 |
| REPLACE(str,a,b) | 用字符串b替换字符串str中所有出现的字符串a |
| STRCMP(s1,s2) | 比较字符串s1和s2 |
| SUBSTRING(str,x,y) | 返回从字符串str x位置起y个字符长度的字串 |

### 数值函数

| 函数 | 功能 |
| :- | :- |
| ABS(x) | 返回x的绝对值 |
| CEIL(x) | 返回大于x的最小整数值 |
| FLOOR(x) | 返回小于x的最大整数值 |
| MOD(x,y) | 返回x/y的模 |
| RAND() | 返回0~1的随机值 |
| ROUND(x,y) | 返回参数x的四舍五入的有y位小数的值 |
| TRUNCATE(x,y) | 返回数字x截断为y位小数的值 |
