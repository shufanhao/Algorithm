# Algorithm
## 排序算法
1. 快速排序--QuickSort
2. 归并排序--MergeSort
3. 堆排序-- HeapSort， 堆排序不是很容易理解

## LeetCode
https://leetcode-cn.com/explore/interview/card/top-interview-questions-easy/

#### 7. 数学
1. Fizz Buzz
2. 计数质数。思路：如果一个数是另一个数的倍数，那这个数肯定不是质数。从2开始，2所有的倍数，都不是质数，然后再从3开始。
3. 3的幂。思路：递归：如果余数是0，除数不是0，则继续递归看余数是否可以整除3。另一个思路：球对数,Log以3为底，求n的对数。
4. 罗马数字转整型。主要是规律（后面的字符比前面的大则减，反之，加）
#### 8. 其他
1. 位1的个数（汉明重量）。思路：某个数字移位，然后和1与，如果是1，则计数加1
2. 两个数字对应二进制不同位置的数目（汉明距离）。思路：先异或，然后求1的个数。
3. 颠倒二进制位。思路：向右移动一位，取到这一位然后将其移动到相反位置，再进行下一次循环
4. 帕斯卡三角形。思路：要理解逻辑，具体看code
5. 有效的括号。思路：充分利用栈，先进后出。如果是 (,{,[则入栈，如果是),}，]的话，则取出栈顶元素，判断是否是(,{,[。如果是，则取出栈顶元素，最后判断栈是否是空
