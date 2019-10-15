#  java-frame框架

<html>
<!--在这里插入内容-->


---

- [x] **SSM[Spring,SpringMVC,mybatis]**




---

- [x] **SpringBOOT**


---


- [x] **SpringCloud**



---

- [x] **Hibarnate**


---

</html>


### java框架部分学习笔记,欢迎大家访问!

```
gantt
dateFormat YYYY-MM-DD
section S1
T1: 2014-01-01, 9d
section S2
T2: 2014-01-11, 9d
section S3
T3: 2014-01-02, 9d
```

表头|表头|表头
---|:--:|---:
内容|内容|内容
内容|内容|内容




```

flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&

```




<a href="#jump_1">来个页内跳转</a>，跳转到文未的：<a id="jump_1">我是页内跳转到的位置</a> ,对应：id="jump_1"
<span style="color: #5bdaed; ">先给点颜色你看看</span>
<span style="color: #AE87FA; ">再给点颜色你看看</span>
<span style="font-size:1.3em;">试试改变字体大小</span>
<span style="font-size:1.3em;font-weight: bold;">改变字体大小，再来个粗体又如何？</span>


$$
        \begin{pmatrix}
        1 & a_1 & a_1^2 & \cdots & a_1^n \\
        1 & a_2 & a_2^2 & \cdots & a_2^n \\
        \vdots & \vdots & \vdots & \ddots & \vdots \\
        1 & a_m & a_m^2 & \cdots & a_m^n \\
        \end{pmatrix}
$$


&#9742;
>https://unicode-table.com/cn/


&#9835;

<table>
<tr>
<td bgcolor=orange>背景色是：orange</td>
</tr>
</table>

:smile:




```
gantt
dateFormat YYYY-MM-DD
section S1
T1: 2014-01-01, 9d
section S2
T2: 2014-01-11, 9d
section S3
T3: 2014-01-02, 9d
```

```
sequenceDiagram
A->>B: How are you?
B->>A: Great!
```

```
graph LR
A-->B
```

```math
E = mc^2
```

### 流程图
```
mermaid
graph TD
   A --> B
```
```  
graph LR
   A --> B 
```
```   
mermaid
graph TB
    c1-->a2
    subgraph one
    a1-->a2
    end
    subgraph two
    b1-->b2
    end
    subgraph three
    c1-->c2
    end
```

```   
mermaid
graph LR
    start[开始] --> input[输入A,B,C]
    input --> conditionA{A是否大于B}
    conditionA -- YES --> conditionC{A是否大于C}
    conditionA -- NO --> conditionB{B是否大于C}
    conditionC -- YES --> printA[输出A]
    conditionC -- NO --> printC[输出C]
    conditionB -- YES --> printB[输出B]
    conditionB -- NO --> printC[输出C]
    printA --> stop[结束]
    printC --> stop
    printB --> stop
```




header 1 | header 2
---|---
row 1 col 1 | row 1 col 2
row 2 col 1 | row 2 col 2

