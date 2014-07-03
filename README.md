练习C语法
========================
完成数据结构算法
--------------------------
###1.树的生成，先序、中序、后序遍历，销毁树
###2.排序
	冒泡
	快速排序（递归）
	堆排序（使用随机数生成数组）
	归并排序
###3.单链表，建表、插入节点、删除节点、打印链表、清空链表、销毁链表
###4.图（邻接表），建图、插入弧、打印图
     
     main.c 老的图文件
     
     realmap.c 新的图文件，全部内容动态生成，支持无向图、有向图，弧可区分单项、双向连接
     
###5.八皇后

     queen.c 可以在给定一个元素的情况下，找到一个四皇后的解
     
     queen02.c 用二维数组实现，可以解决n皇后问题，得出n皇后的解个数

###6.数学问题
     
     Palindromic.cpp  判断回文数，分配内存实现
     Palindromic02.c  判断回文数，int变量实现
###7.数组中的数字问题
     i)   在一个每个数字出现2次的数组中，找到只出现一次的两个数字   findAbnormal.cpp
     ii)  在一个每个数字出现3次的数组中，找到只出现一次的数字
          find1in3.cpp      使用32个元素的数组
          singleNumber.cpp  三个变量，O(n)内得到结果，每次都是在上次循环的基础上更新
