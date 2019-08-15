##引用

>这是一段引用的文本
>>这也是一段引用的文本
>>>这还是一段引用的文本
>>>>这个引用可以有 N 层

##分割线

---
---

***
****

##文本格式

这是一段没有任何格式的文本

*这段文本斜体显示*
*The paragraph is italic*
_The paragraph is italic_

**这段文本加粗显示**
**The paragraph is bold**
__The paragraph is bold__

***这段文本斜体加粗显示***
***The paragraph is italic and bold***
___The paragraph is italic and bold___

~~这段文本包含删除线~~
~~The paragraph has a delete line~~

##加载图片
![blockChain](https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/u=702257389,1274025419&fm=27&gp=0.jpg "区块链")

##超链接
[超链接](http://jianshu.com "简书")
<http://jianshu.com>

##无序列表
- 列表项一
+ 列表项二
* 列表项三
>注意：符号和内容之间必须加一个空格
##有序列表
1. 列表项一
2. 列表项二
3. 列表项三

##嵌套列表
1. 一级列表
   - 二级菜单
   + 二级菜单
   * 二级菜单
2. 一级列表
3. 一级列表

##表格
序号|姓名|技能|排行
----|---|---|----
1   |刘备|哭 |老大
2   |关羽|打 |老二
3   |张飞|骂 |老三

##代码
`let msg = 'Hello World'`   单行代码

---
代码块
``` javascript
function print(msg) {
    console.log(msg)
}
print('Hello World')
```
##流程图
``` flow
st=>start: 开始
op=>operation: 操作
cond=>condition: Yes or No ?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```
