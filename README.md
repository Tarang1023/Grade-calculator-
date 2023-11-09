#include <stdio.h>
// library file
int main()
//main file under which the programme is executed
{
    int num1,num2,num3,num4,num5;
    int percentage; // declaration of variables
    printf("Enter your subject 1 marks: ");
    scanf("%d",&num1);
    printf("Enter your subject 2 marks: ");
    scanf("%d",&num2);
    printf("Enter your subject 3 marks: ");
    scanf("%d",&num3);
	printf("Enter your subject 4 marks: ");
    scanf("%d",&num4);
	printf("Enter your subject 5 marks: ");
    scanf("%d",&num5); //getting input from receiver
    int total= num1 + num2 + num3 + num4 + num5; //calculating total marks
    printf("Your total marks scored are:%d\n", total); 
    percentage = total/5; //calculating percentage scored
    printf("your score percentage is:%d%%\n",percentage);
    if(total<= 500 && total>=450){
        printf("You got A grade \n");
		printf("BRAVO !\n");
    }
    else if (total<=450 && total>=300){ 
        printf("You got B grade \n");
        printf("GOOD JOB !\n");
    }
    else if ( total<=300 && total>=150){
        printf("You got C grade \n");
        printf("WORK HARDER !\n");
    }
    else{
        printf("You Failed \n");
        printf("DISAPPOINTMENT ! \n");
    }
	//using else if to calculate the grade scored by the student
}
