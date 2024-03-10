# change-integer-in-c-
#include <stdio.h>

//交換兩個變數
void swap(int*x,int*y){
    
    int tem ;
    tem=*x;
    *x=*y;
    *y=tem;
}     
    
    
int main()
{
    int a=10;
    int b=20;
    printf("交換前a,b的值分別為:\n");
    printf("a=%d\n",a);
    printf("b=%d\n",b);
    
    
    swap(&a,&b);
    printf("交換後a,b的值分別為:\n");
    printf("a=%d\n",a);
    printf("b=%d\n",b);
    return 0;
    
   
   
   
   
   
   
   

    return 0;
}
    
   
    

