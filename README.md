# flowchart-
>项目截图
![image](https://github.com/yuanyuannetwork/flowchart-/blob/master/1.jpg)
![image](https://github.com/yuanyuannetwork/flowchart-/blob/master/2.jpg)

# 注释

st=>start: 开始

e=>end: 结束

操作块

op1=>opration: 第一个操作块

op2=>opration: 第二个操作块

判断块

cond1=>condition: 第一个判断

cond2=>condition: 第二个判断

输入输出块 inputoutput

io1=>inputoutput: 输入输出块1

io2=>inputoutput: 输入输出块2

子任务块

sub1=>subroutine: 子任务1

sub2=>subroutine: 子任务2

并行任务！！

para=>parallel: parallel tasks

para(path1, bottom)->sub1(left)->op1

para(path2, right)->op2->e

判断流程控制

cond1(yes)->op1  #yes 的时候回到 op1

cond1(no)->e   #no 的时候 去结束

位置指定

cond1(no)->op2(right)->op1 #控制 op2 位置置于右边，再由op2 返回 op1 (好像不能向左)

还可以这样 cond1(no,right)

cond1(yes)->e 
