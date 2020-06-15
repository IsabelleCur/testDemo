#<center>WEEK4</center>
##Algorithm

25.k个一组翻转链表

<https://leetcode-cn.com/problems/reverse-nodes-in-k-group/>

对联表的翻转不熟悉，首先要会链表的翻转。然后“隔离法”，不用考虑两组之间的元素位置关系，隔离并考虑相关指针pre(即上一组的tail，tail->next是首元素的next)就会正确，考虑则多余且易错。
##Review
MIT Linear Algebra公开课11课，终于看完，接下来主要是备考期末。

##Tip
操作系统做的两个项目：(Java)

电梯：减法带绝对值: ：寻找响应向上键的最近上行（只能通过电梯状态值另行判断）电梯：min{abs(楼层数-电梯所在层数)}，Java没有无符号整数（不是主要原因），若未加绝对值，电梯高于楼层时，值为负，与本意不同。

动态内存分配：ArrayList删除前面的元素后面元素的索引会变，所以最好先删后面的元素再删前面的元素。
##Share

<https://v.qq.com/x/page/f0384gb5mq8.html>