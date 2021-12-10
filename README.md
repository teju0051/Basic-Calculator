#include<stdio.h>

void main() { float num1,num2; char op; float result;

printf("\n CALCULATOR\n");

printf("\n creator: tejas sushil shinde\n");

//the above code will display the header of the program.


printf("\n Enter the first number:  ");

scanf("%f",&num1);

//here user will enter the first number

printf("\n Enter the operation:  ");

scanf(" %c",&op);

//here user will select the operation between ( +,-,*,/)

printf("\n Enter the second number: ");

scanf("%f",&num2);

//here user will type second 

switch(op)

{

    case'+'  :result=num1+num2;
              printf("\n Answer = %f" ,result);
              break;
              //this operation will do addition of the input
              
    case'-'  :result=num1-num2;
              printf("\n Answer =%f" ,result);
              break;
              //this code will subtract  the input
              
    case'*'  :result=num1*num2;
              printf("\n Answer =%f" ,result);
              break;
              //this code will multiply the input
            
    case'/'  :result=num1/num2;
              printf("\n Answer = %f" ,result);
              break;
              //this code will divide the input
    default:
    printf("\n The operation is invalid");
    // this code will display when user don't use the operation correctly
}

}


