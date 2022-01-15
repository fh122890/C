# sort()函数

## 用法
1. 头文件#include < algorithm>和using namespace std;
2. 它使用的排序方法是类似于快排的方法，时间复杂度为n*log2(n)
3. Sort函数有三个参数：(1)排序的数组的起始地址;(2)结束的地址（最后一位要排序的地址);(3)排序的方法，可以是从大到小也可是从小到大，还可以不写第三个参数，此时默认的排序方法是从小到大排序。


## 实例
~~~ c++
#include<iostream>
#include<algorithm>
using namespace std;
int main()
{
    int a[] = {1,4,6,7,3,2,};
    sort(a,a+5);
    for(int j = 0; j < 5; j++)
        cout << a[j] << endl;

    return 0;
}
~~~
