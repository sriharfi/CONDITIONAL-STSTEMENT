#include<stdio.h>
main()
{
printf("pick an a item: \n1. pen \n2. books\n3. scale\n4. eraser");
int choice=0;
scanf("%d", choice);
switch(choice)
{
case 1:
       printf("you picked your pen.");
case 2:
       printf("you picked your books.");
case 3:
      printf("you picked your scale.");
case 4:
       printf("you picked your eraser.");
 deafult  :printf("invaild choicd");
 }
 }
