#include <stdio.h>

int main (int argc, char *argv[]) {

    double num1, num2, sum, res, mul, div;
    int op1=0, op2=0;

    do{
    printf("Enter num1: ");
    scanf("%lf",&num1);
    printf("Enter num2: ");
    scanf("%lf",&num2);

    printf("Select Operation:\n1.Sum\n2.Substraction\n3.Multiplication\n4.Division\n>>");
    scanf("%d",&op1);

    switch (op1)
    {
    case 1:
        sum=num1+num2;
        printf("The sum is: %lf\n",sum);
        break;
    case 2:
        res=num1-num2;
        printf("Substration is: %lf\n",res);
        break;
    case 3:
        mul=num1*num2;
        printf("Multiplicaction is: %lf\n",mul);
        break;
    case 4:
        if(num2!=0){
            div=num1/num2;
            printf("Division is: %lf\n",div);
        }else{
            printf("Can not divide 0\n");
        }
        break;
    default:
        printf("No option selected\n");
        break;
    }
    printf("Would you like to make another operation?\n1.Y\n2.N\n>>");
    scanf("%d",&op2);
    }while(op2==1);

    return 0;
}