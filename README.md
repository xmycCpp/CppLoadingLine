# CppProgressBar
这是一个用c++做成的进度条程序
This is a progress bar program by c++
**用法：**
`loading(当前进度, 总进度, 进度条填充符号, 未达成进度填充符号)
注意：需要在循环内使用，不然只输出一次进度条
通常当前进度为一个变量
进度不是百分比，程序会自己计算百分比

## 例如
for (int i = 0; i <= 100; i++)
    {                           
        usleep(50000);     
       loading(i, 100, "");
    }
//   从1到100  隔0.5秒增加1进度
## 导入：
`#include "progressBar.hpp"`
请确保文件在和程序同一目录下
