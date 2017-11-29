# leetcode
*代码实现为javascript*
1、Two Sum   ---easy
=====
题目：给定一个整数数组，两个数字的返回索引，它们加到一个特定的目标。
-----
思路：一个双循环，第二个循环从第一个循环下标的下一个作为起点。(暴力解法，此解法算是刚拿到题目首先想到的解法。)<br>
另一种解法：提高降低时间复杂度，增加空间复杂度。

2、Add Two Numbers   ---medium
=====
题目：给出了两个非空链表，表示两个非负整数。数字以倒序存储，每个节点都包含一个数字。添加两个数字并将其作为一个链表返回。(给定两个长度不定的单链表，数字以倒序存储，两个单链表相加，返回一个单链表)
-----
思路：当时第一次看到题目的时候，没有看懂题意，对链表的知识掌握不多，忘记了链表的定义和一些基本的操作。题目中括号里是之后自己对题目的理解。题目中并没有规定两个链表的长度是否相同，就要考虑长度不同的情况。至于倒序存储还没有明白（如果接下来搞明白，会来记录一下）

3、Longest Substring Without Repeating Characters  ---medium
=====
题目：给定一个字符串，查找没有重复字符的最长子字符串的长度。
-----
思路：双指针，一个标记头指针的位置，一个标记尾指针的位置，没有找到指定字符尾指针移动，否则头指针移动，另一个值记录最大maxlength。


