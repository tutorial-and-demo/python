# 列表

## 定义

使用方括号就能定义一个列表。列表元素类型不限。
```python
list = [1,2,3,4]
```

## 访问列表中的值

列表可以使用下标访问，从0开始。和其他语言不同，python中下标可以是负数，表示从右往左访问，从-1开始。

对于长度为`n`的列表`l`，从左到右第`i`个元素可以使用`l[i-1]`访问，也可以使用`l[i-1-n]`来访问。

除了使用下标访问，还可以使用`l[start:end:step]`来截取列表。

## 更新和删除列表

可以直接通过下标来更新或删除列表。删除列表元素需要使用`del`关键字：
```python
l[i] = 12345
del l[i]
```

## 列表操作符

和字符串一样，列表可以使用`+`拼接，可以使用`+`重复。

## python内置函数和列表内置函数

python内置函数如下：
1. len(list):输出列表中的元素数目。
2. max(list)/min(list):输出列表中的最大/最小元素。
3. list(seq):将元组转化为列表。

列表内置函数如下：
1. `append(obj)`:在列表末尾追加元素obj。
2. `count(obj)`:输出obj在列表中出现的次数。
3. `extend(seq)`:将序列seq中的值附加到列表末尾。
4. `index(obj)`:找出第一个匹配obj的索引位置。
5. `insert(index, obj)`:将元素插入列表。
6. `list.pop([index=-1])`：移除列表中的一个元素（默认最后一个元素），并且返回该元素的值。
7. `list.remove(obj)`：移除列表中某个值的第一个匹配项。
8. `list.reverse()`：反向列表中元素。
9. `list.sort( key=None, reverse=False)`：对原列表进行排序。
10. `list.clear()`：清空列表。
11. `list.copy()`：复制列表。
