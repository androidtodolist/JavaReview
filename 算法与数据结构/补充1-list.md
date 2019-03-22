
<font size=4 color=#D2691E> ArrayList LinkedList vector的区别 2019年3月18日（状态：记录-解决）</font>

***

<image src="pic/pic_array.png" width=400>

* 1.ArrayList和LinkedList的区别：<br>
ArrayList是用数组实现的，访问的时间复杂度为 O(1)，添加删除的平均时间复杂度为O(N)  
LinkedList的是双向链表实现，访问的平均时间复杂度为O(N)，添加删除的平均时间复杂度为O(1)

* 2.ArrayList和vector的区别: <br>
ArrayList是线程不同步的。  
Vector是线程同步的，所以Vector性能低一些。  
此外，Collections提供了一系类的线程同步的实现
  ```java
  Collections.synchronizedList()
  Collections.synchronizedSet()
  Collections.synchronizedMap()
  ```


* 3.Stack和Vector的区别：<br>
Stack继承Vector，并提供了 push pop peek empty 等方法

