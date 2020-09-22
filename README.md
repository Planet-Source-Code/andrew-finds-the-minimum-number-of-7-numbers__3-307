<div align="center">

## Finds the Minimum number of 7 numbers


</div>

### Description

This program finds the Minimum number of 7 numbers entered.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Andrew](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/andrew.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |C\+\+ \(general\)
**Category**       |[Math](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/math__3-12.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/andrew-finds-the-minimum-number-of-7-numbers__3-307/archive/master.zip)





### Source Code

```
#include <iostream.h>
#include <conio.h>
void main()
{
clrscr();
int i,num,min;
for(i=1;i<=7;i++)
{
cout<<"please enter a value #"<<i<<":";
cin>>num;
if (i==1)
min=num;
else
if(num<min)
min=num;
}
cout<<"the smallest number is :"<<min;
}
```

