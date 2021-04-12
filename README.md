# lab-2
#include <stdio.h> //conenct lib
#include<locale.h>
#include<math.h>

int main(void) {
int x;
int y;
float z;
int c;
float d;
printf("\n vkacitb chuclo x=");
scanf("%d",&x);
printf("\n vkacitb chuclo y=");
scanf("%d",&y);
z = fmod(y,x);
c = x/y;
d = x*y;
printf("zalushok chucel: %f\n",z);
printf("cila chactuna: %d\n",c);
printf("dobutok: %f\n",d);
return 0;
}
