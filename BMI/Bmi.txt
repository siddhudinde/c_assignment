#include <stdio.h>
int main()
{
    float Wt;
    float Ht;
    float Bmi;
    
    printf("Enter the weight(in kg)");
    scanf("%f",&Wt);
    printf("\nEnter the height(in cm)");
    scanf("%f",&Ht);
    Ht=Ht/100;
    float X=Ht*Ht;
    Bmi=Wt/X;
    
    if 
    (Bmi<18)
    {
        printf("The weight is in underweight %f",Bmi);
    }
    else if
    (Bmi<25)
    {
        printf("The weight is normal weight %f",Bmi);
        
   
    }
    else
    {
       printf("The weight is overweight %f",Bmi);  
    }
    return 0;
    
}