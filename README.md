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
![Test Image](https://www.google.com/search?q=memes&tbm=isch&imgil=x15aIW54IS_TKM%253A%253BdE3bFWijGvDcCM%253Bhttp%25253A%25252F%25252Fmemesvault.com%25252F&source=iu&pf=m&fir=x15aIW54IS_TKM%253A%252CdE3bFWijGvDcCM%252C_&usg=__x7U8PaulkI3pVVMmg5y0U-X7d_A%3D&biw=1600&bih=799&ved=0ahUKEwjU79zG_rnLAhWhk4MKHQ_BDYQQyjcIQA&ei=z2_jVpTMG6GnjgSPgregCA#imgrc=x15aIW54IS_TKM%3A)

##Background

| Library       | Function      |
| ------------- | ------------- |
| iostream      | main function |
| fstream       | file I/O      |
| cmath         | Math Library  |

##Results

##References
<http://www.cplusplus.com/doc/tutorial/files/> 
