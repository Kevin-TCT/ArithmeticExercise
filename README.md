# ArithmeticExercise
Company algorithm exercise

##序号：#2
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


##序号：#3
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