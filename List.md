一、列表：字符串数组

1、创建列表

​	list_of_name = [a, b, ...... ] 

2、访问元素

​	使用索引 -1 可访问最后一个元素

3、添加元素

​	末尾添加：append('xxx')方法

​	插入：insert(index, 'xxx')方法

4、删除元素

​	del语句：del list_name[index];

​	pop方法：pop(); 可删除列表末尾元素，返回被删除的元素；

​					   pop(index);删除任意位置处元素，返回被删除的元素；

​	remove方法：remove('string');要删除的值可能出现多次，该方法只删除靠前的一个指定的元素，若需要删除所有相同的元素，可以使用循环；

5、组织列表

​	排序

​		sort()方法：对列表元素按照ASCII码从小到大进行排序；可传递参数sort(reverse=True)，进行从大到小排序

​		sorted()方法：对列表元素的拷贝进行排序

​	反转元素

​		reverse()方法：反转列表元素的顺序

​	获取列表元素长度

​		len()函数：len(list_name)

6、遍历列表

​	for循环：item是临时变量

​		for item in list_of_item:

【tips】Python根据缩进来判断代码行与前一个代码行的关系；

7、创建特殊的列表：数字列表

​	函数range(a, b)：返回值为包含大于a小于b的整数元素的列表；

​			range(a, b, t)：返回值为a = a+t < b的整数元素的列表；

【tips】**表示乘法运算

8、对数字列表的计算函数

​	min(list_of_name)

​	max(list_of_name)

​	sum(list_of_name)

9、列表解析

​	将for循环和创建新元素的代码合并成一行，并自动附加新元素。

​	eg：square = [value**2 for value in range(1, 11)]

10、处理列表的部分元素：切片

​	list_of_name[a : b]：返回下标为a到b-1的元素。

​	list_of_name[ : b]：返回下标为0到b-1的元素。

​	list_of_name[a : ]：返回下标为a到列表末尾的元素。

【tips】a, b可以是负数，表示倒数第几个元素；

11、复制列表

​	list_of_name_a = [.....];

​	list_of_name_b = list_of_name_b; #a, b指向同一份数据；

​	list_of_name_b = list_of_name_a[ : ];#b是a的一份拷贝，这时存在有两份数据；

12、元组：不可变的列表，使用圆括号而不是方括号

​	元组元素不能被修改，但是可以给存储元组的变量赋值，即重新定义整个元组。



