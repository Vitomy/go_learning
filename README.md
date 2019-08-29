# go_learning
集合go的编程技巧 多协程编程 分布式 数据库MySQL Linux操作系统讲解

## go 深入理解系列
* [深入理解文本类型](./go_coding/go_text.md)
* [深入理解defer](./go_coding/go_defer.md)
* [实验楼游戏-2048](./go_project/g2048.go)
* [mysql增删查改实现](./go_project_mysql/mysql_test.go)
* [go深入理解interface{}](./go_coding/interface_test/go_interface.md)
* [go深入理解context]
* [go深入理解channel，锁]()
* [go 认识IO](./go_lib/goio_test.go)

## go alorigthm
* [two Sum，map的判断不是==，而是value,ok:=map[]...](./go_leetcode/two_sum.go)
* [Three Sum，三个指针 发现快排还是慢](./go_leetcode/three_Sum.go)
* [Three Sum Closet，发现太慢了！应该有更快的方法，但是空间用的贼少，典型时间换空间](./go_leetcode/threeSumCloset.go)
* [倒数第n个，k-n+1](./go_leetcode/theNththeend.go)
* [longestPalindrome最长回文，其实都是从中间开始向左右遍历，一个一个往后遍历](./go_leetcode/longestProline.go)

## go 数据结构与算法之美
* [链表实现CRUD，链表反转，环的检测，链表合并递归完美](./go_alorigthm/listgo/golist_test.go)
* [栈的实现，用切片实现，自动扩容](./go_alorigthm/stackgo/stackgo_test.go)
* [go实现冒泡，插入，选择排序](./go_alorigthm/sortgo/sortgo_test.go)
* [go实现快排，归并排序 求第K大元素 O(n)的时间复杂度](./go_alorigthm/quickMergeSort/quickMergeSort_test.go)
* [桶排序，计数排序，基数排序O(n)](./go_alorigthm/bucketSort/bucketgo_test.go)
* [二分查找以及其变体，十个二分九个错](./go_alorigthm/binarySearch/binarySearch_test.go)
* [跳表实现我就不实现了，我们需要知道这个性能可以媲美红黑树](https://github.com/wangzheng0822/algo/blob/master/go/17_skiplist/skiplist.go)
* [LRU缓存算法，实现了一个散列表和双向链表](./go_alorigthm/hashTable/hashTable_test.go)
* [二叉树中序遍历，前序遍历循环递归实现](./go_alorigthm/binaryTree/binaryTree_test.go)
* [普通二叉查找树，容易退化，衍生红黑树，红黑树平衡，但是实现难度大，但是性能求稳定，不求实现但求原理的理解以及解决的问题](./go_alorigthm/binaryTreeSearch/binaryTreeSearch_test.go)
* [堆排序，一个完全二叉树，基于数组，持续堆化，建堆排序，在数组的操作，一般搞下标就好了](./go_alorigthm/heapSort/heapSort_test.go)
* [图的广度与深度遍历](./go_alorigthm/graphgo/graph_test.go)
* [多模式串匹配实现敏感词过滤算法，trie树经典，比较有意思，等工作了再搞](./go_alorigthm/morePattern/morePattern_test.go)
* [贪心算法 我有贪心策略，此策略必有优解](./go_alorigthm/greedyAlgo/greedy_test.go)
* [分而治之，了解一下MapReduce的分治思想，遇到大问题，解决成小问题](./)
* [回溯算法(蝴蝶效应)8皇后与背包问题，要么选要么不选](./go_alorigthm/backDynamic/eightQueens_test.go)
* [动态规划]()

## go k8s实战

## go MySQL系列
* [mysql是怎么执行语句?](./MySQL/go_connect_transcation.md)
* [mysql表级锁，行锁以及全局锁](./MySQL/lock.md)
* [mysql事务隔离？](./MySQL/transaction.md)
* [唯一索引与普通索引的选择,change buffer!=redo log](./MySQL/chooseIndex.md)
