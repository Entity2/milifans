---
title: '映射与集合论'
published: 2026-05-24
description: '知识分享'
tags: ["高等代数"]
category: 'Study'
draft: false
---

## 映射 
### 单射
$<==>$A中不同元素在f下的像不相等<br/>
$<==>$像相等可以推出被映射的元素相等
### 满射
$<==>\forall b∈B,∃a∈A, s.t.$   $b=f(a)$
### 双射
既是单射又是满射,称为双射
##  结论
### 定理1
数域$\mathbb{K}$上的两个有限维线性空间$V$和$V'$同构<br/>
$<==>$$\dim V$=$\dim V'$<br/>
并且满足交换律结合率
### 定理2
$dim (V_1 +V_2)=dim V_1 +dim V_2 - dim (V_1 \cap V_2)$
### 推论
$\mathbb{K}$上任一$n$维线性空间都有:
$$
V \cong \mathbb{K}
$$
### 定义1
$f: A \rightarrow B$   $g: B \rightarrow C$ <br/>
则称$gf: A \rightarrow C$ <br/>
$(gf)(a) =g(f(a)),∀a∈A$ <br/>
$gf$是$g$与$f$的乘积<br/>
映射乘法满足结合率,不满足交换律
### 定义2
if  $f: A \longrightarrow A$<br/>
      $x \longmapsto x$ <br/>
则称$f$是$A$的一个恒等变换,并记作:
$$
1_A
$$
### 定义3
设$f: A \longrightarrow B$<br/>
if$∃g:B \longrightarrow A$   $s.t.$ $gf=1_A$    $fg=1_B$<br/>
则称$f$为可逆映射,$g$是$f$的逆映射<br/>
并显然有:$f^{-1}$唯一
### 定理1
$f: A \rightarrow B$可逆
$<==>f$是双射
## 集合论
### 定义1
if $S$是由自身的非空子集的并集构成,且这组非空子集的交集是$\varnothing$<br/>
则称这些子集是$S$的一个划分
### 定义2
设$S\neq \varnothing$ ,$W$是$S\times S$的一个子集<br/>
则称$W$是$S$上的一个二元关系<br/>
如果$(a,b)∈W$则称$a$与$b$有$W$关系<br/>
记作:
$$
a \underset{W}{\sim} b
$$
或者
$$
a\sim b
$$
### 定义3
$S$的一个二元关系若满足:
$$
a \sim a,∀a∈S(反身性)
$$
$$
a\sim b==>b\sim a(对称性)
$$
$$
a\sim b,b\sim c,==>a\sim c(传递性)
$$
那么我们称$\sim$是$S$的一个等价关系
