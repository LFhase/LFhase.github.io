---
layout: post
title: "Abstract-Algebra-001"
date: 2017-9-21 18:00
category: "design"
tag: Algebra
---

> Mathematic is never too shy to show people its beauty.
> This is my Self-paced Notes of 《A First Course in Abstract Algebra》

<br>
*A First Course in Abstract Algebra : Representing and Manipulating Information*

<br><br>
我们首先从一个最基本的最漂亮的公理出发：
- **Least Integer Axiom**:
- 对每一个自然数的非空子集，总有一个最小的整数
- There is a smallest integer in every nonempty subset C of
the natural numbers N.

这个公理简洁而有力，它充分体现了一个自下往上的朴素的可数性，用几个推理来解释即：
- **Least Criminal**:
- Let k be a natural number, and let $$ S(K), S(K+1), ..., S(n), ... $$ be a list of statements. If some of these statements are false, then there is a first false statements.

由这条推论出发，可以十分显然地引出**数学归纳法**的第一种形式：
- Mathematical Induction:
- Given statements S(n), one for each natural number n, suppose that:
	- (i)	**Base step**: S(0) is true;
	- (ii) **Inductive Step**: if S(n) is true, then S(n+1) is true.
- Then S(n) is true for all natural numbers n.

与此同时，我们注意到**Least Integer Axiom**不仅适用于自然数集，也使用于其非空子集，还适用于一些包含负数的整数集合，由此可以引出更常用的**数学归纳法**的第二种形式：
- **Definition**: The **predecessors** of a natural number $$ n>= 1 $$ are the natural numbers k with k < n, namely, 0, 1, 2, 3, ..., n-1 (0 has no predecessor)
- **Second Form of Induction**:
- Let S(n) be a family of statements, one for each natural number n, and suppose that:
	- (i) S(0) is true;
	- (ii) if S(k) is true for all predecessors k of n, then S(n) is itself true.
- Then S(n) is true for all natural numbers n.

众所周知，**数学归纳法** 应用极广，能解决那些无法直接获得结论却想知道真假的命题，这无不体现了**Least Integer Axiom**的美丽之处。但是，回过头来，**数学归纳法** 忽略了一些数学上精巧的工具与方法，终归是有欠缺。
