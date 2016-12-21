# SortDemo
原生：NSComparator && NSDescriptor
1. 选择排序
2. 冒泡排序
3. 快速排序
4. 插入排序

1：冒泡排序：冒泡排序（Bubble Sort），是一种计算机科学领域的较简单的排序算法。 它重复地走访过要排序的数列，一次比较两个元素，如果他们的顺序错误就把他们交换过来。走访数列的工作是重复地进行直到没有再需要交换，也就是说该数列已经排序完成。


2：选择排序： 选择排序：比如在一个长度为N的无序数组中，在第一趟遍历N个数据，找出其中最小的数值与第一个元素交换，第二趟遍历剩下的N-1个数据，找出其中最小的数值与第二个元素交换......第N-1趟遍历剩下的2个数据，找出其中最小的数值与第N-1个元素交换，至此选择排序完成。选择排序是不稳定的排序方法。（找弟弟法）


3：插入排序：直接插入排序(Insertion Sort)的基本思想是：每次将一个待排序的记录，按其keyword大小插入到前面已经排好序的子序列中的适当位置，直到所有记录插入完毕为止。

			 设数组为a[0…n-1]
       
			1.      初始时。a[0]自成1个有序区，无序区为a[1..n-1]。令i=1
      
			2.      将a[i]并入当前的有序区a[0…i-1]中形成a[0…i]的有序区间。
			
			3.      i++并反复第二步直到i==n-1。
      
￼![image](https://github.com/MrTung/SortDemo/blob/master/SortDemo/Screenshots/C8BC1433-B7B4-4440-900B-84AD4BE994C1.png?raw=true)


4：快速排序：快速排序是当遇到较大数据时,排序快,高效的方法该方法的基本思想是：

			1．先从数列中取出一个数作为基准数。
      
			2．分区过程，将比这个数大的数全放到它的右边，小于或等于它的数全放到它的左边。
      
			3．再对左右区间重复第二步，直到各区间只有一个数。
      
			简单地理解就是,找一个基准数(待排序的任意数,一般都是选定首元素),把比小于等于基准数的元素放到基准数的左边,把大于基准数的元素放在基准数的右边.排完之后,在把基准数的左边和右边各看成一个整体,  左边:继续选择基准数把小于等于基准数的元素放到基准数的左边,把大于基准数的元素放在基准数的右边,右边也是一样..直到各区间只有一个数位置.
      快速排序之所比较快，因为相比冒泡排序，每次交换是跳跃式的。每次排序的时候设置一个基准点，将小于等于基准点的数全部放到基准点的左边，将大于等于基准点的数全			部放到基准点的右边。这样在每次交换的时候就不会像冒泡排序一样每次只能在相邻的数之间进行交换，交换的距离就大的多了。因此总的比较和交换次数就少了，速度自然			就提高了。当然在最坏的情况下，仍可能是相邻的两个数进行了交换。因此快速排序的最差时间复杂度和冒泡排序是一样的都是O(N2)，它的平均时间复杂度为O(NlogN)。

￼￼![image](https://github.com/MrTung/SortDemo/blob/master/SortDemo/Screenshots/E944A7A1-DD8C-4031-9E29-95C8A215F22C.png?raw=true)

