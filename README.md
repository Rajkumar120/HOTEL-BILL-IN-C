// HOTEL-BILL-IN-C
#include<stdio.h>
#include<conio.h>
#include<stdlib.h>
int totalbill;
int c1=0;
int c2=0;
int c3=0;
int c4=0;
int c5=0;
int c6=0;
int c7=0;
int c8=0;
int c9=0;
int c10=0;
int c11=0;
int c12=0;
char s1[100];
char s2[100];
char s3[100];
char s4[100];
char s5[100];
char s6[100];
char s7[100];
char s8[100];
char s9[100];
char s10[100];
char s11[100];
char s12[100];
void tiffin();
void meals();
void softdrinks();
void main()
{
    int c;
    do
    {
        printf("\n----MENU OF SR UNIVERSITY HOTEL----\n");
        printf("\n1.TIFFINS\n");
        printf("\n2.MEALS\n");
        printf("\n3.SOFT DRINKS\n");
        int x,y;
        printf("\nSelect your food items type:\n");
        scanf("%d",&x);
        switch(x)
        {
        case 1:
            tiffin();
            break;
        case 2:
            meals();
            break;
        case 3:
            softdrinks();
            break;
        default:
        main();
        printf("\nInvalid choice of food items\n");
        }
        printf("\nDo u want to order some more food items:\n");
        printf("1.Yes\n2. No\n");
        scanf("%d",&c);
    } while(c==1);
    if(c!=1)
    printf("\n***************************\n");
    if(c1==1)
    {
    printf("\n%s\n",s1);
    }
    if(c2==1)
    {
    printf("\n%s\n",s2);
    }
    if(c3==1)
    {
    printf("\n%s\n",s3);
    }
    if(c4==1)
    {
    printf("\n%s\n",s4);
    }
    if(c5==1)
    {
    printf("\n%s\n",s5);
    }
    if(c6==1)
    {
    printf("\n%s\n",s6);
    }
    if(c7==1)
    {
    printf("\n%s\n",s7);
    }
    if(c8==1)
    {
    printf("\n%s\n",s8);
    }
    if(c9==1)
    {
    printf("\n%s\n",s9);
    }
    if(c10==1)
    {
    printf("\n%s\n",s10);
    }
    if(c11==1)
    {
    printf("\n%s\n",s11);
    }
    if(c12==1)
    {
    printf("\n%s\n",s12);
    }
    printf("\n****************************\n");
    printf("\n****************************\n");
    printf("total bill of food items: %d\n", totalbill);
    printf("\n****************************\n");
    printf("\n*****THANK YOU VISIT AGAIN****\n");

}
void tiffin()
{
    printf("\nThe tiffins available are:\n");
    printf("\n1.IDLI\n");
    printf("\n2.DOSA\n");
    printf("\n3.VADA\n");
    printf("\n4.PURI\n");
    printf("\ncost of 1 IDLI=30rs\n\ncost of 1 DOSA=30rs\n\ncost of 1 VADA=30\n\ncost of 1 PURI=40rs\n");
    int y;
    int n;
    printf("\nEnter your favourite tiffin:\n\n");
    scanf("%d",&y);
    switch(y)
    {
    case 1:
        printf("\nHow many plates of IDLIES you wannt:\n");
        scanf("%d",&n);
       printf("\nThe cost of total IDLIES is: %d\n",n*30);
        totalbill+=n*30;
        sprintf(s1,"The cost of IDLIES :%d",n*30);
        c1++;
        break;
    case 2:
        printf("\nHow many plates of DOSA you wannt:\n");
        scanf("%d",&n);
        printf("\nThe cost of total DOSA is :%d\n",n*30);
        totalbill+=n*30;
        sprintf(s2,"The cost of DOSA: %d",n*30);
        c2++;
        break;
    case 3:
        printf("\nHow many plates of VADAS you wannt:\n");
        scanf("%d",&n);
        printf("\nThe cost of total VADAS is: %d\n",n*30);
        totalbill+=n*30;
        sprintf(s3,"The cost of VADAS :%d",n*30);
        c3++;
        break;
    case 4:
        printf("\nHow many plates of PURIS  you wannt:\n");
        scanf("%d",&n);
       printf("\nThe cost of total PURIS is: %d\n",n*40);
        totalbill+=n*40;
        sprintf(s4,"The cost of PURIS :%d",n*40);
        c4++;
        break;
    }
}
void meals()
{
    printf("\nThe available meals are:\n");
    printf("\n1.EGG FRIED RICE\n");
    printf("\n2.VEG FRIED RICE\n");
    printf("\n3.CHICKEN BIRYANI\n");
    printf("\n4.MUTTON BIRYANI\n");
    printf("\ncost of plate EGG FRIED RICE=100rs\n\ncost of 1 plate VEG FRIED RICE=100rs\n\ncost of 1 plate CHICKEN BIRYANI=200\n\ncost of 1 MUTTON BIRYANI=300rs\n");
    int y;
    int n;
    printf("\nEnter your favourite Meals:\n");
    scanf("%d",&y);
    switch(y)
    {
    case 1:
        printf("\nHow many plates of EGG FRIED RICE you want:\n");
        scanf("%d",&n);
        printf("\nThe cost of total plates EGG FRIED RICE of is: %d\n",n*100);
        totalbill+=n*100;
        sprintf(s5,"The cost of EGG FRIED RICE :%d",n*100);
        c5++;
        break;
    case 2:
        printf("\nHow many plates of VEG FRIED RICE you wannt:\n");
        scanf("%d",&n);
        printf("\nThe cost of total VEG FRIED RICE is:%d\n",n*100);
        totalbill+=n*100;
        sprintf(s6,"The cost of VEG FRIED RICE :%d",n*100);
        c6++;
        break;
    case 3:
        printf("\nHow many plates of CHICKEN BIRYANI you wannt\n");
        scanf("%d",&n);
        printf("\nThe cost of total plates of CHICKEN BIRYANI is: %d\n",n*200);
        totalbill+=n*200;
        sprintf(s7,"The cost of CHICKEN BRIYANI :%d",n*200);
        c7++;
        break;
    case 4:
        printf("\nHow many plates of MUTTON BIRYANI  you wannt\n");
        scanf("%d",&n);
        printf("\nThe cost of total plates of MUTTON BIRYANI is: %d\n",n*300);
        totalbill+=n*300;
        sprintf(s8,"The cost of MUTTON BIRYANI :%d",n*200);
        c8++;
        break;
    }
}
void softdrinks()
{
    printf("\nThe available softdrinks are:\n");
    printf("\n1.pepsi\n");
    printf("\n2.7up\n");
    printf("\n3.sprite\n");
    printf("\n4.brothers juice\n");
    printf("\ncost of pepsi=30rs\n\ncost of 7up = 30rs\n\ncost of sprite=30\n\ncost of brothers juice=40rs\n");
    int y;
    int n;
    printf("\nEnter your favourite softdrink:\n");
    scanf("%d",&y);
    switch(y)
    {
    case 1:
        printf("\nHow many Pepsi you want:\n");
        scanf("%d",&n);
        printf("\nThe cost of total pepsi is:%d\n",n*30);
        totalbill+=n*30;
        sprintf(s9,"The cost of PEPSI :%d",n*30);
        c9++;
        break;
    case 2:
        printf("\nHow many 7up's you wannt:\n");
        scanf("%d",&n);
        printf("\nThe cost of total 7up's is:%d\n",n*30);
        totalbill+=n*30;
        sprintf(s10,"The cost of 7up's :%d",n*30);
        c10++;
        break;
    case 3:
        printf("\nHow many spirites you wannt:\n");
        scanf("%d",&n);
        printf("\nThe cost of total sprites  is:%d\n",n*30);
        totalbill+=n*30;
        sprintf(s11,"The cost of spirites :%d",n*30);
        c11++;
        break;
    case 4:
        printf("\nHow many brothers juice  you wannt:\n");
        scanf("%d",&n);
        printf("\nThe cost of total brothers juiceis:%d\n",n*40);
        totalbill+=n*40;
        sprintf(s12,"The cost of brothers juice :%d",n*40);
        c12++;
        break;
    }
}
