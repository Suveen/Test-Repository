#C++ File Input Output

##Introduction

This is a brief document on how to **read and write data on files** in a C++ program. This is totally based on my knowledge I acquired from my college courses. 

The following sections are covered:

  1. Reading from a file, also called Input File Stream: *ifstream*
 
  2. Writing to a file, also called Output File Stream: *ofstream*

##Code
```
#include <iostream>

#include <fstream>

using namespace.std
 
 int main (void)
 
{

   ifstream File_1;
 
   double data;
 
   File_1.open("Data.txt");
 
   if (File_1.fail())
 
   {
      cout<< "Can't Open File" <<endl;
 
     return -1;
 
    }
  
  File_1>>data;
  
  File_1.close;
  
 return 0;
  
}
```
##Image
![Test Image](http://41.93.48.204/club/wp-content/uploads/2015/10/programming.jpg)
![Test Image](http://41.93.48.204/club/wp-content/uploads/2015/10/programming.jpg)
##Background

| Library       | Function      |
| ------------- | ------------- |
| iostream      | main function |
| fstream       | file I/O      |
| cmath         | Math Library  |

##Results

##References
<http://www.cplusplus.com/doc/tutorial/files/> 
