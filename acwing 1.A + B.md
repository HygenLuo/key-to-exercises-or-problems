#### [ACWing.1 A + B](https://www.acwing.com/problem/content/1/)
#### 题目描述：
输入两个整数，求这两个整数的和是多少。

#### 输入格式
输入两个整数A,B，用空格隔开，0≤A,B≤ $2^8$
#### 输出格式
输出一个整数，表示这两个数的和

#### 样例输入：
>     3 4     
#### 样例输出：
>     7
#### 解题思路：
只要对 `A`，`B`两个数进行加法计算，因此其时间复杂度为`O(1)`，且加法得出最高值只有$2*10^8$，因此只需要用`int`即可。

##### 代码
```cpp
#include<iostream>
using namespace std;

int main(){
    int a,b;
    cin >> a >> b;
    
    cout << a + b;
    
    return 0;
}
```
