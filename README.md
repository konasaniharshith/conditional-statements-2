# conditional-statements-2
done by harshith
#include<stdio.h>
int main()
{
   int a;
   scanf("%d",&a);
   switch(a)
   {
    case 1:
     printf("Food item - Biryani\nPrice - Rs 450\n");
     break;
    case 2:
     printf("Food item - roti\nPrice - Rs 100\n);
     break;
    case 3:
     printf("Food item - pasta\nPrice - 150\n");
     break;
    case 4:
     printf("Food item - manchuriya\nPrice - 100\n");
     break;
     case 5:
      printf("Food item - rice\nPrice - 120\n");
      break;
     default:
     printf("I am not hungry");
    }
     return 0;
}





