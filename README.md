#C++ File Input Output

##Introduction

The first sentence about to move to new paragraph. 

The second paragraph begins. Testing 1,2,3. Testing 1,2,3. Testing 1,2,3. Testing 1,2,3. Testing 1,2,3. Testing 1,2,3.
Testing 1,2,3. Testing 1,2,3. Testing 1,2,3. Testing 1,2,3. Testing 1,2,3. Testing 1,2,3. Testing 1,2,3. Testing 1,2,3.
Testing 1,2,3. Testing 1,2,3. **Testing 1,2,3.**

List

 -First point
 
 -*Second point*
 
 -Third point
 
##Code
`#include <iostream>`

`#include <fstream>`

 `using namespace.std`
 
 `int main (void)`
 
`{`

 `  ifstream File_1;`
 
 `  double data;`
 
 `  File_1.open("Data.txt");`
 
 `  if (File_1.fail())`
 
 `  {`
 `    cout<< "Can't Open File" <<endl;`
 
 `    return -1;`
 
  `  }`
  
  `File_1>>data;`
  
  `File_1.close;`
  
  `return 0;`
  
`}` 
 
##Background

##Results

##References
