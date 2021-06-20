#include<stdio.h>
int main()
{

   int choice;
   printf("enter the item you would like(1 to 5):");
   scanf("%d",&choice);
   swtch(choice)
   {
   
      case 1:
             printf("pizza\n");
             printf("price=239");
             break;
      case 2:
             printf("burger\n");
             printf("price=129");
             break;
      case 3:
            printf("pasta\n");
            printf("price=179");
            break;
      case 4:
            printf("french fries\n");
            printf("price=99");
            break;
      case 5:
            printf("sandwich\n");
            printf("price=149");
            break;
            printf("invalid choice");
            break;
    }
    return 0;
    }
