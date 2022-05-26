# c-programs-
#include<stdio.h>
#include<windows.h>
#include<string.h>
// for sleep function //
// this helps and allows us to wait for just a current thread for a set amount time 
int main(void)
{ printf("to check whether the enter key is pressed or not\n");
printf("try to press any key other than enter, if nothing happens\n");
printf("press enter key twice!");
	while(1)
	{
	 //	if(getchar()== '\n')
	 {
	 char str[32];
	 gets(str);
	 if(strcmp(str,"")==0)
		{
			printf("Enter Key Is Pressed");
			Sleep(1000);
			//here we wait for check printed message 
			break;
			}
		}
 	}
	return(0);
}
