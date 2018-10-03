# BlackJack
Creat a 21 points game
#include<stdio.h>
#include<string.h>
int main()
{
    printf("游戏开始\n");
    char in1[500];
    while(1)
    {
        scanf("%s",in1);
        if(strlen(in1)!=1)
            continue;
        if(in1[0]=='y')
            printf("OK\n");
        else if(in1[0]=='n')
            printf("NotBad\n");
        else if(in1[0]=='q')
        {
            printf("Bye");
            break;
        }
    }
    return 0;

}
