# 8.STORAGE-CLASSES-2
#include <stdio.h> 
   
  
static int count = 5;   	 
  main() { 
   while(count--) 
   {       func(); 
   }    return 0; 
} 

{ 
   static int i = 5;   
   i++; 
   printf("i is %d and count is %d\n", i, count); 
}
