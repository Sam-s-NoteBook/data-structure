# 知识点总结

二叉查找树的特征：

- 是二叉树

- 左子树内所有节点权值比当前节点小，右子树内所有节点权值比当前节点大

- 左右子树均为二叉查找树

空树满足该性质，所以空树也是二叉查找树。

## ASL

TODO

## AVL树

AVL是一种平衡二叉搜索树。通过旋转维护平衡。

### 判断平衡的方法

AVL定义节点的平衡因子为`左子树的高度 - 右子树的高度`。AVL定义平衡的条件为`树上所有节点的平衡因子都为 0, 1, -1 中的一个`。

不满足平衡的条件时，认为AVL失衡。

### 维护平衡的方法

当AVL失衡时对AVL进行调整。可知，当AVL进行插入删除操作时有可能失衡。显然可知失衡时平衡因子仅可能为 $2$ 或 $-2$。

AVL用单旋和双旋维护平衡。其中单选分为左单旋、右单旋，双旋分为左右双旋和右左双旋。

TODO：补充旋转的内容。

## 红黑树

红黑树是一种平衡二叉搜索树。考试范围比较小。细节不多写，以后在博客里写。

### 判断平衡的方法