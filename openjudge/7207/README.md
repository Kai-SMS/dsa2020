# 250202: 神奇的幻方

**总时间限制:** 1000ms    **内存限制:** 65535KB

## 描述

幻方是一个很神奇的N*N矩阵，它的每行、每列与对角线，加起来的数字和都是相同的。我们可以通过以下方法构建一个幻方。（阶数为奇数）

1. 第一个数字写在第一行的中间
2. 下一个数字，都写在上一个数字的右上方：
   - 如果该数字在第一行，则下一个数字写在最后一行，列数为该数字的右一列
   - 如果该数字在最后一列，则下一个数字写在第一列，行数为该数字的上一行
   - 如果该数字在右上角，或者该数字的右上方已有数字，则下一个数字写在该数字的下方

## 输入

一个数字N（N<=20）

## 输出

按上方法构造的2N-1 * 2N-1的幻方

## 样例输入
```
3
```

## 样例输出
```
17 24 1 8 15
23 5 7 14 16
4 6 13 20 22
10 12 19 21 3
11 18 25 2 9
```
