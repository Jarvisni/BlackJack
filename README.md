# BlackJack
Creat a 21 points game
#include<stdio.h>
#include<string.h>

int main()
{
	char in1[100];
	
	printf("游戏开始\n");
	scanf("%s",in1);
	
	
	if (strlen(in1)>1)
	return 0;
	else
	switch(in1[0])
	{
		case 'y':
			printf("OK");break;
		case 'n':
			printf("Not bad");break;
		case 'q':
			printf("Bye");break;
	}
 	return 0;
    
}
