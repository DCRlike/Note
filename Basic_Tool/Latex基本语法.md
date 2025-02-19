## 公式块
- 一般公式块
    被`$` 包裹, 比如`$a,b,c$`  显示为$a,b,c$
- 特殊公式块
    被`$$`包裹, 会独立成段, 比如 `$$\sum_{i=1}^n a_i$$ `
    $$\sum_{i=1}^n a_i$$
## 语法
使用`$sym$` 即可, 比如
### 基本符号
- + -  ! |abs|
- a..z(Rust语法 bushi)
- 1..infinity
- < > |(整除)
- .
### 强制使用latex语法的
- 任何不能直接由键盘打出来的
    比如 $\leq \geq \times \div \cdot \ast \in$
    他们应被表示为
```Latex
$\leq$ $\deq$ $\times$ $\div$ $\dot$ $\cdot$ $\in$
```
- CJK有关字符
- 与字母标记有关
    比如 $a[i]=1$, $a \bmod b$,  $a\neq b$ 
```latex
$a_i=1$、$a\bmod b$、$a\neq b$
```     
## 语法大全
### 字母变形
`$\bar{a}$`  $\bar{a}$
`$\hat{a}` $\hat{a}$ 
`$\widehat{a}`  $\widehat{a}$ 
`$\vec{a}`  $\vec{a}$
### 标准函数
`$\exp_a b=a^b$`  $\exp_a b=a^b$
`$\sin a$`  $\sin a$
`$\left\vert a\right\vert$`  $\left\vert a\right\vert$
`$\min(x,y)` $\min(x,y)$
### 界限
`$\min x \max y$` $\min x    \max y$
`$\lim u$`  $\lim u$
### 映射
`$\Pr j$` $Pr j$
### 微分和导数
`$dt$` $dt$
`$mathrm{d}t$` $\mathrm{d}t$
`$\prime$`   $\prime$
`$\backprime$`  $\backprime$
`$f^\prime$`  $f^\prime$
`$f'$` $f'$
 `$f''$`  $f''$ 
`$f^{(3)}$`  $f^{(3)}$ 
`$\dot{y}$`  $\dot{y}$ 
`$\ddot{y}$`$\ddot{y}$
### 类字母符号
`$\infty$` $\infty$
### 根号
`$\sqrt[n]{n}$`  $\sqrt[n]{n}$
### 运算符
`$+ - \pm \mp \times \div$`
$+ - \pm \mp \times \div$
`$\boxplus \boxminus \boxtimes \boxdot$`
$\boxplus \boxminus \boxtimes \boxdot$
`$\oplus \ominus \otimes \oslash \odot$`
$\oplus \ominus \otimes \oslash \odot$
`$\bigoplus \bigotimes \bigodot$`
$\bigoplus \bigotimes \bigodot$
### 集合
`$\{ \} \emptyset \varnothing$`
$\{ \} \emptyset \varnothing$
`$\in \notin \not\in \ni \not\ni$`
$\in \notin \not\in \ni \not\ni$
### 逻辑符号
`$\forall \exists \nexists$`
$\forall \exists \nexists$
### 上下标
#### 上标
`$a^2$` $a^2$
#### 下标
`$a_2$` $a_2$
##### 组合起来
`$a^{2+2} a_{i,j}$` $a^{2+2} a_{i,j}$
`$a^2_2$` $a^2_2$
`$a^{2,3}_{3,4}$` $a^{2,3}_{3,4}$
##### 前置
`${}^2_1\!X^3_4$` 用`\!` 与字母隔开 ${}^2_1\!X^3_4$
### 向量
`$\vec{x} \overleftarrow{AB} \overrightarrow{AB} \widehat{AB}$`
$\vec{x} \overleftarrow{AB} \overrightarrow{AB} \widehat{AB}$
### 求和
`$\sum_{i=1}^na_i` $\sum_{i=1}^na_i$
`$\sum\limits_{i=1}^na_i$` $\sum\limits_{i=1}^na_i$
### 极限
`$\lim_{n\to\infty}x_n$`  $\lim_{n\to\infty}x_n$
### 分数
`$\frac{1}{2}$`  $\frac{1}{2}$
