# Code2
#include <stdio.h>
#include <string.h>

int main ()
{
  char string, ch,Lower Alpha,Upper Alpha,digit;
  int count = 0, i,c=0,ct=0;
printf(" Enter the string \n");
scanf("%s",string);
int n = strlen(string);
if (n<8)
printf("password is too much small");
for (i = 0; string[i] >='A' && <='Z'; i++) {
count++;
Upper Alpha = count; }

for (i = 0; string[i] >='a' && <='z'; i++) {
 c++;
Lower Alpha = c; }
for (i = 0; string[i] >='0' && <='9'; i++) {
 ct++;
digit = ct; }
printf(""'%c' is Lower character.", Lower Alpha );
printf(""'%c' is Lower character.", Upper Alpha );
printf(""'%c' is Lower character.", digit );
}
