## 同构
给定两棵树T1和T2.如果T1可以通过若干次左右孩子互换就变成T2,则我们称两棵树是"同构"的.

![](http://qiniu.rearib.top/20191912/1611-i.png)

### 二叉树的表示
- 先在一行中给出该树的结点数,随后N行
- 第i行对应编号第i个结点, 给出该结点中存储的字母、其左孩子结点的编号、右孩子结点的编号
- 如果孩子结点为空,则在相应位置上给出"-".
- 节点可以是无序的

![](http://qiniu.rearib.top/20191912/1613-O.png)

![](http://qiniu.rearib.top/20191912/1614-B.png)

> 使用数组的方式

![](http://qiniu.rearib.top/20191912/1616-U.png)

> 结构数组表示二叉树:静态链表

![](http://qiniu.rearib.top/20191912/1618-E.png)

### 程序框架搭建
![](http://qiniu.rearib.top/20191912/1620-6.png)

### 如何建二叉树
![](http://qiniu.rearib.top/20191912/1621-S.png)

### 如何判别两二叉树同构
![](http://qiniu.rearib.top/20191912/1621-w.png)

![](http://qiniu.rearib.top/20191912/1622-L.png)





