# markdown
markdown 轻量级标记语言
## mark基本操作
1. 标题

使用#号标记，可以表示1-6级标题，随#个数递增。如：
```markdown
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```
注：最后一个#与文字间一定要有一个空格。
2. 换行
- 直接在一句话后面敲两个空格
- 两句话之间加一个空行
- 如果你在编辑的时候，想让一行文字分成几段在显示的时候换行，就在中间加:<br/>

3. 字体
```markdown
*斜体文本*
_斜体文本_
**粗体文本**
__粗体文本__
***粗斜体文本***
___粗斜体文本___
```
4. 分割线

markdown中分割线，能是你的文章结构更加清楚
```markdown
***

* * *

*****

- - -

----------
```
---
5. 删除线，下划线。
```markdown
~~删除线~~
<u>下划线</u>
```
6. 序列

markdown可以通过 * - + 开头作为列表标记。
```markdown
* 第一行
* 第二行

- 第一行
- 第二行

+ 第一行
+ 第二行
```
7. 有序
```markdown
1. 
2.
```
数字后面加空格即可
8. 区块

markdown区块是在段落开头使用 “>”，依然是紧跟空格（可以分层）

```markdown
> markdown
>> mk基础
```
效果
> markdown
>> mk基础
## markdown进阶
1. 代码插入
```markdown
```代码语言（可以忽略）
代码块
```结尾
```
2. 插入链接
```markdown
[链接名称](链接地址)
```
示例：

[github](https://github.com)
3. 插入图片
```markdown
![图片描述](图片地址)
```
示例：

![示例](../QQ截图20221130224241.png)
4. 表格
```markdown
| -

```
示例：

| 表头1                       |     表头2      |          表头3 |
|:--------------------------|:------------:|-------------:|
| 表格内容111111111111111111111 |     表格内容     |         表格内容 |
5. HTML元素

使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑


 




