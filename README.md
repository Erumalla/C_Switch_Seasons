//C_Switch_Seasons
//C Programming
#include<stdio.h>
//Checking the Season by the month input number
int main()
{
    int month;
//Taking input from the user
    printf("Enter Month Number:\n 1 = January\n 2 = February\n 3 = March\n 4 = April\n 5 = May\n 6 = June\n 7 = July\n 8 = August\n 9 = September\n 10 = October\n 11 = November\n 12 = December\n");
    scanf("%d",&month);
//Season checking by the input number
    switch(month){
    case 1:
    case 2:
        printf("Season: Winter");
        break;
    case 3:
    case 4:
        printf("Season: Spring");
        break;
    case 5:
    case 6:
        printf("Season: Summer");
        break;
    case 7:
    case 8:
        printf("Season: Monsoon");
        break;
    case 9:
    case 10:
        printf("Season: Autumn");
        break;
    case 11:
    case 12:
        printf("Season: Prewinter");
        break;
    default:
        printf("Please check the entered input");
        }
        return 0;
        }
