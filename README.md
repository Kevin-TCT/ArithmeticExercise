# [JAVA常用的八种排序算法](./arithmetic/src/main/java/com/kevin/arithmetic/sort/README.md)
<br/>
<br/>

# ArithmeticExercise
Company algorithm exercise
<br/>
## [序号：#2 找出单独出现的数字](./arithmetic/src/main/java/com/kevin/arithmetic/Solution2.java)
难度：有挑战  时间限制：1000ms  内存限制：10M
描述
给出N个数字。其中仅有一个数字出现过一次，其他数字均出现过两次，找出这个出现且只出现过一次的数字。要求时间和空间复杂度最小。

输入
输入多个数字，每个数字以空格分开，回车结束

输出
输出内容为只出现过唯一一次的数字

输入样例
10 10 11 12 12 11 16

输出样例
16
<br/>
<br/>
## [序号：#3 大数相减](./arithmetic/src/main/java/com/kevin/arithmetic/Solution3.java)
难度：有挑战  时间限制：1000ms  内存限制：100M
描述
两个长度超出常规整形变量上限的大数相减，请避免使用各语言内置大数处理库，如 Java.math.BigInteger 等。

输入
有 N 行测试数据，每一行有两个代表整数的字符串 a 和 b，长度超过百位。规定 a>=b，a, b > 0。
测试结果可以用 linux 小工具 bc进行测试是否正确。

输出
返回表示结果整数的字符串。

输入样例
1231231237812739878951331231231237812739878951331231231237812739878951331231231237812739878951331231231237812739878951331231231237812739870 - 89513312312312378127398789513312312312378127398789513312312312378127398789513

1231231237812739878951331231231237812739878951331231231237812739878951331230000000000000000000000001 - 331231231237812739878951331231231

输出样例
1231231237812739878951331231231237812739878951331231231237812650365639018918853110413950365639018918853110413950365639018918853110413950357

1231231237812739878951331231231237812739878951331231231237812739878620099998762187260121048668768770
<br/>
<br/>
## [序号：#4 最长连续数列](./arithmetic/src/main/java/com/kevin/arithmetic/Solution4.java)
难度：困难  时间限制：1000ms  内存限制：10M
描述
输入一个乱序的连续数列，输出其中最长连续数列长度，要求算法复杂度为  O(n)  。

输入
54,55,300,12,56

输出
3

输入样例
100,4,200,1,3,2

54,55,300,12

1

5,4,3,2,1

1,2,3,4,5,6

输出样例
4

2

1

5

6
<br/>
<br/>
## [序号：#5 找出旋转有序数列的中间值](./arithmetic/src/main/java/com/kevin/arithmetic/Solution5.java)
难度：一般  时间限制：1000ms  内存限制：10M
描述
给出一个有序数列随机旋转之后的数列，如原有序数列为：\[0,1,2,4,5,6,7] ，旋转之后为: \[4,5,6,7,0,1,2]。
假定数列中无重复元素，且数列长度为奇数。
求出旋转数列的中间值。如数列\[4,5,6,7,0,1,2]的中间值为4。

输入
4,5,6,7,0,1,2

输出
4

输入样例
1

1,2,3

4,5,6,7,0,1,2

12,13,14,5,6,7,8,9,10

输出样例
1

2

4

9
<br/>
<br/>
## [序号：#6 交叉队列](./arithmetic/src/main/java/com/kevin/arithmetic/Solution6.java)
难度：有挑战  时间限制：1000ms  内存限制：10M
描述
给出三个队列 s1，s2，s3 ，判断 s3 是否是由 s1 和 s2 交叉得来。
如：s1 为 aabcc ， s2 为 dbbca。
当 s3 为 aadbbcbcac 时，返回 true（即将 s1 拆成三部分： aa，bc，c 分别插入 s2 对应位置）
否则返回 false。

输入
aabcc,dbbca,aadbbcbcac

输出
true

输入样例
aabcc,dbbca,aadbbcbcac

aabcc,dbbca,aadbbbaccc

a,b,ab

a,b,ba

a,b,ac

abc,bca,bcaabc

abc,bca,aabbcc

输出样例
true

false

true

true

false

true

false
<br/>
<br/>
## [序号：#7 第一个缺失正数](./arithmetic/src/main/java/com/kevin/arithmetic/Solution7.java)
难度：有挑战  时间限制：1000ms  内存限制：10M
描述
给出一个无序的数列，找出其中缺失的第一个正数，要求复杂度为 O(n)
如：\[1,2,0]，第一个缺失为3。
如：\[3,4,-1,1]，第一个缺失为2。

输入
1,2,0

输出
3

输入样例
1,2,0

3,4,-1,1

-1,-3,-5

1,2,3

-1,-10,0

输出样例
3

2

1

4

1
<br/>
<br/>

## [序号9：移除K位得到最小值](./arithmetic/src/main/java/com/kevin/arithmetic/Solution9.java)
难度：困难
时间限制：500ms
内存限制：10M

描述

有一行由 N 个数字组成的数字字符串，字符串所表示的数是一正整数。移除字符串中的 K 个数字，使剩下的数字是所有可能中最小的。

假设：

字符串的长度一定大于等于 K

字符串不会以 0 开头

输入

一行由 N 个数字组成的数字字符串（0 < N < 20），和一个正整数 K（K < N），两个数据由空格隔开，如：1432219 3。

输出

移除 K 位后可能的最小的数字字符串。 如 1432219 移除 4, 3, 2 这 3 个数字后得到 1219，为所有可能中的最小值。

输入样例
1432219 3
10200 1

输出样例
1219
200

解题思路：

每次只需要找出前三位的最大值移除就行
<br/>

## [序号10: 爬楼梯](./arithmetic/src/main/java/com/kevin/arithmetic/Solution10.java)
难度：一般 时间限制：1000ms 内存限制：10M <br/>
描述：<br/>
在你面前有一个n阶的楼梯，你一步只能上1阶或2阶。 请问计算出你可以采用多少种不同的方式爬完这个楼梯。<br/>
输入: 一个正整数，表示这个楼梯一共有多少阶<br/>
输出: 一个正整数，表示有多少种不同的方式爬完这个楼梯<br/>
输入样例<br/>
5<br/>
10<br/>
输出样例<br/>
8<br/>
89<br/>

解题思路：<br/>
斐波拉契数组<br/>

<br/>

## [序号11：构建短字符串](./arithmetic/src/main/java/com/kevin/arithmetic/Solution11.java)
难度：一般
时间限制：1000ms
内存限制：10M<br/>
描述<br/>
给定任意一个较短的子串，和另一个较长的字符串，判断短的字符串是否能够由长字符串中的字符组合出来，且长串中的每个字符只能用一次。<br/>
输入<br/>
一行数据包括一个较短的字符串和一个较长的字符串，用一个空格分隔，如： ab aab bb abc aa cccc uak areuok<br/>
输出<br/>
如果短的字符串可以由长字符串中的字符组合出来，返回字符串 “true”，否则返回字符串 "false"，注意返回字符串类型而不是布尔型。<br/>
输入样例<br/>
a b<br/>
aa ab<br/>
aa aab<br/>
uak areuok<br/>

输出样例<br/>
false<br/>
false<br/>
true<br/>
true<br/>

解题思路：<br/>
双层循环，时机复杂度O(n^2)  （待优化）<br/>

<br/>

## [序号87: 美丽字符串](./arithmetic/src/main/java/com/kevin/arithmetic/Solution87.java)<br/>

难度：困难  时间限制：1000ms  内存限制：10M<br/>
描述<br/>
定义一个美丽字符串，对于字符串S，S中只包含小写的a-z字符，存在2条规则：<br/>
规则1：S中每个字符出现的次数一样，如abc，每个字符出现1次，aabbcc，每个字符出现2次<br/>
规则2：添加或删除S中的一个字符后，使得S中每个字符出现的次数一样，如abca，删除一个字符a，则变为abc后每个字符出现1次
             又例如aabcbbcc,添加一个字符a，则变为aabcbbcca，每个字符出现3次
对于字符串S，若满足规则1，2中任意一条规则，则称为美丽的字符串<br/>
输入<br/>
一个字符串S，只包含a-z的小写字符<br/>
输出<br/>
判断该字符串是否为美丽的字符串，若是则输出YES，若不是则输出NO<br/>
输入样例<br/>
abc<br/>
aabbccc<br/>
aaccbd<br/>

输出样例<br/>
YES<br/>
YES<br/>
NO<br/>