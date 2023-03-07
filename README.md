# data-structure-project-game-abcdasd
#include<stdio.h>
#include<stdlib.h>
#include<string.h>
int main();
int score=0;
int T_score=0;
struct node
{
    int score;
    struct node *next;
};struct node *start=NULL;
void viewyourscore()
{struct node *temp;
    int T_score=0;
    if(start==NULL)
    {
        printf("\n your total is 0");
    }
    else
    {
        temp=start;
        printf("\n your score is :");
        while(temp!=NULL){
            printf("\t%d",temp->score);
            T_score=T_score+temp->score;
            temp=temp->next;
        }
        printf("\n \n\nyour total score %d",T_score);
    }
}

void insertatbegin(int score)
{
    struct node *newnode;
    newnode=(struct node*)malloc(sizeof(struct node));
    newnode->score=score;
    newnode->next=NULL;
    if(start==NULL)
        start=newnode;
    else{
        newnode->next=start;
        start=newnode;
    }
        }
void addinggame()
{int a_score=0,i,n;
    char c[1];
    printf("\t\t\t\t\t\t*******************************\n\n");
    printf("\t\t\t\t\t\t\tWELCOME TO ADDITION GAME\n\n");
    printf("\t\t\t\t\t\tWe ensure your mental ability\n\n");
    printf("\t\t\t\t\t\t*******************************\n\n\n\n");
    printf("\n ADD THE NUMBER OF FIGURES PRESENT BELOW\n\n\n\t\t");
   for(i=0;i<3;i++)
     {
         printf("\t\U0001F402");
     }
    printf("\t\t+\t");
    for(i=0;i<3;i++)
     {
         printf("\t\U0001F402");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==6)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         a_score=a_score+10;
     }
    printf("\n your score is %d\n",a_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(a_score);
            main();
    }
    printf("\t your score is %d\n",a_score);
     printf("\t\t");
    for(i=0;i<2;i++)
     {
         printf("\t\U0001F403");
     }
    printf("\t\t+\t");
    for(i=0;i<5;i++)
     {
         printf("\t\U0001F403");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==7)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         a_score=a_score+10;
     }
    printf("\n your score is %d\n",a_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(a_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<3;i++)
     {
         printf("\t\U0001F404");
     }
    printf("\t\t+\t");
    for(i=0;i<2;i++)
     {
         printf("\t\U0001F404");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==5)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         a_score=a_score+10;
     }
    printf("\n your score is %d\n",a_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(a_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<6;i++)
     {
         printf("\t\U0001F646");
     }
    printf("\t\t+\t");
    for(i=0;i<3;i++)
     {
         printf("\t\U0001F646");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==9)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         a_score=a_score+10;
     }
    printf("\n your score is %d\n",a_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(a_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<7;i++)
     {
         printf("\t\U0001F648");
     }
    printf("\t\t+\t");
    for(i=0;i<6;i++)
     {
         printf("\t\U0001F648");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==13)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         a_score=a_score+10;
     }
    printf("\n your score is %d\n",a_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(a_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<8;i++)
     {
         printf("\t\U0001F640");
     }
    printf("\t\t+\t");
    for(i=0;i<5;i++)
     {
         printf("\t\U0001F640");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==13)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         a_score=a_score+10;
     }
    printf("\n your score is %d\n",a_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(a_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<9;i++)
     {
         printf("\t\U0001F690");
     }
    printf("\t\t+\t");
    for(i=0;i<7;i++)
     {
         printf("\t\U0001F690");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==16)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         a_score=a_score+10;
     }
    printf("\n your score is %d\n",a_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(a_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<10;i++)
     {
         printf("\t\U0001F692");
     }
    printf("\t\t+\t");
    for(i=0;i<10;i++)
     {
         printf("\t\U0001F692");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==20)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         a_score=a_score+10;
     }
    printf("\n your score is %d\n",a_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(a_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<9;i++)
     {
         printf("\t\U0001F693");
     }
    printf("\t\t+\t");
    for(i=0;i<8;i++)
     {
         printf("\t\U0001F694");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==17)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         a_score=a_score+10;
     }
    printf("\n your score is %d\n",a_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(a_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<13;i++)
     {
         printf("\t\U0001F699");
     }
    printf("\t\t+\t");
    for(i=0;i<9;i++)
     {
         printf("\t\U0001F699");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==22)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         a_score=a_score+10;
     }
    printf("\n your score is %d\n",a_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(a_score);
            main();
    }
    printf("\t\t");
    for(i=0;i<14;i++)
     {
         printf("\t\U0001F400");
     }
    printf("\t\t+\t");
    for(i=0;i<13;i++)
     {
         printf("\t\U0001F400");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==27)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         a_score=a_score+10;
     }
    printf("\n your score is %d\n",a_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(a_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<2;i++)
     {
         printf("\t\U0001F648");
     }
    printf("\t\t+\t");
    for(i=0;i<5;i++)
     {
         printf("\t\U0001F648");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==7)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         a_score=a_score+10;
     }
    printf("\n your score is %d\n",a_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(a_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<2;i++)
     {
         printf("\t\U0001F647");
     }
    printf("\t\t+\t");
    for(i=0;i<5;i++)
     {
         printf("\t\U0001F647");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==7)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         a_score=a_score+10;
     }
    printf("\n your score is %d\n",a_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(a_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<11;i++)
     {
         printf("\t\U0001F405");
     }
    printf("\t\t+\t");
    for(i=0;i<9;i++)
     {
         printf("\t\U0001F405");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==20)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         a_score=a_score+10;
     }
    printf("\n your score is %d\n",a_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(a_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<5;i++)
     {
         printf("\t\U0001F407");
     }
    printf("\t\t+\t");
    for(i=0;i<12;i++)
     {
         printf("\t\U0001F407");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==17)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         a_score=a_score+10;
     }
    printf("\n your score is %d\n",a_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(a_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<16;i++)
     {
         printf("\t\U0001F410");
     }
    printf("\t\t+\t");
    for(i=0;i<14;i++)
     {
         printf("\t\U0001F410");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==30)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         a_score=a_score+10;
     }
    printf("\n your score is %d\n",a_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(a_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<9;i++)
     {
         printf("\t\U0001F413");
     }
    printf("\t\t+\t");
    for(i=0;i<9;i++)
     {
         printf("\t\U0001F413");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==18)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         a_score=a_score+10;
     }
    printf("\n your score is %d\n",a_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(a_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<7;i++)
     {
         printf("\t\U0001F415");
     }
    printf("\t\t+\t");
    for(i=0;i<9;i++)
     {
         printf("\t\U0001F415");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==16)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         a_score=a_score+10;
     }
    printf("\n your score is %d\n",a_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(a_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<11;i++)
     {
         printf("\t\U0001F418");
     }
    printf("\t\t+\t");
    for(i=0;i<5;i++)
     {
         printf("\t\U0001F418");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==17)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         a_score=a_score+10;
     }
    printf("\n your score is %d\n",a_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(a_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<2;i++)
     {
         printf("\t\U0001F648");
     }
    printf("\t\t+\t");
    for(i=0;i<5;i++)
     {
         printf("\t\U0001F648");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==7)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         a_score=a_score+10;
     }
    printf("\n your score is %d\n",a_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(a_score);
            main();
    }
     printf("\t\t");
    printf("\n your a_score is %d",a_score);
    insertatbegin(a_score);
}
void subtractinggame()
{int s_score=0,i,n;
    char c[0];
    printf("\t\t\t\t\t\t*******************************\n\n");
    printf("\t\t\t\t\t\t\tWELCOME TO SUBTRACTION GAME\n\n");
    printf("\t\t\t\t\t\tWe ensure your mental ability\n\n");
    printf("\t\t\t\t\t\t*******************************\n\n\n\n");
    printf("\n SUBTRACT THE NUMBER OF FIGURES PRESENT BELOW\n\n\n\t\t");
   for(i=0;i<4;i++)
     {
         printf("\t\U0001F402");
     }
    printf("\t\t-\t");
    for(i=0;i<3;i++)
     {
         printf("\t\U0001F402");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==1)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         s_score=s_score+10;
     }
    printf("\n your score is %d\n",s_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(s_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<5;i++)
     {
         printf("\t\U0001F403");
     }
    printf("\t\t-\t");
    for(i=0;i<2;i++)
     {
         printf("\t\U0001F403");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==3)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         s_score=s_score+10;
     }
    printf("\n your score is %d\n",s_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(s_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<3;i++)
     {
         printf("\t\U0001F404");
     }
    printf("\t\t-\t");
    for(i=0;i<2;i++)
     {
         printf("\t\U0001F404");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==1)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         s_score=s_score+10;
     }
    printf("\n your score is %d\n",s_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(s_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<6;i++)
     {
         printf("\t\U0001F646");
     }
    printf("\t\t-\t");
    for(i=0;i<3;i++)
     {
         printf("\t\U0001F646");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==3)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         s_score=s_score+10;
     }
    printf("\n your score is %d\n",s_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(s_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<7;i++)
     {
         printf("\t\U0001F648");
     }
    printf("\t\t-\t");
    for(i=0;i<6;i++)
     {
         printf("\t\U0001F648");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==1)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         s_score=s_score+10;
     }
    printf("\n your score is %d\n",s_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(s_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<8;i++)
     {
         printf("\t\U0001F640");
     }
    printf("\t\t-\t");
    for(i=0;i<5;i++)
     {
         printf("\t\U0001F640");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==3)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         s_score=s_score+10;
     }
    printf("\n your score is %d\n",s_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(s_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<9;i++)
     {
         printf("\t\U0001F690");
     }
    printf("\t\t-\t");
    for(i=0;i<7;i++)
     {
         printf("\t\U0001F690");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==2)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         s_score=s_score+10;
     }
    printf("\n your score is %d\n",s_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(s_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<10;i++)
     {
         printf("\t\U0001F692");
     }
    printf("\t\t-\t");
    for(i=0;i<10;i++)
     {
         printf("\t\U0001F692");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==0)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         s_score=s_score+10;
     }
    printf("\n your score is %d\n",s_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(s_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<9;i++)
     {
         printf("\t\U0001F693");
     }
    printf("\t\t-\t");
    for(i=0;i<8;i++)
     {
         printf("\t\U0001F694");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==1)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         s_score=s_score+10;
     }
    printf("\n your score is %d\n",s_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(s_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<13;i++)
     {
         printf("\t\U0001F699");
     }
    printf("\t\t-\t");
    for(i=0;i<9;i++)
     {
         printf("\t\U0001F699");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==4)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         s_score=s_score+10;
     }
    printf("\n your score is %d\n",s_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(s_score);
            main();
    }
    printf("\t\t");
    for(i=0;i<14;i++)
     {
         printf("\t\U0001F400");
     }
    printf("\t\t-\t");
    for(i=0;i<13;i++)
     {
         printf("\t\U0001F400");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==1)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         s_score=s_score+10;
     }
    printf("\n your score is %d\n",s_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(s_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<5;i++)
     {
         printf("\t\U0001F648");
     }
    printf("\t\t-\t");
    for(i=0;i<2;i++)
     {
         printf("\t\U0001F648");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==3)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         s_score=s_score+10;
     }
    printf("\n your score is %d\n",s_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(s_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<10;i++)
     {
         printf("\t\U0001F647");
     }
    printf("\t\t-\t");
    for(i=0;i<3;i++)
     {
         printf("\t\U0001F647");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==7)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         s_score=s_score+10;
     }
    printf("\n your score is %d\n",s_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(s_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<11;i++)
     {
         printf("\t\U0001F405");
     }
    printf("\t\t-\t");
    for(i=0;i<9;i++)
     {
         printf("\t\U0001F405");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==3)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         s_score=s_score+10;
     }
    printf("\n your score is %d\n",s_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(s_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<12;i++)
     {
         printf("\t\U0001F407");
     }
    printf("\t\t-\t");
    for(i=0;i<5;i++)
     {
         printf("\t\U0001F407");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==7)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         s_score=s_score+10;
     }
    printf("\n your score is %d\n",s_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(s_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<16;i++)
     {
         printf("\t\U0001F410");
     }
    printf("\t\t-\t");
    for(i=0;i<12;i++)
     {
         printf("\t\U0001F410");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==4)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         s_score=s_score+10;
     }
    printf("\n your score is %d\n",s_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(s_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<10;i++)
     {
         printf("\t\U0001F413");
     }
    printf("\t\t+\t");
    for(i=0;i<2;i++)
     {
         printf("\t\U0001F413");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==8)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         s_score=s_score+10;
     }
    printf("\n your score is %d\n",s_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(s_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<9;i++)
     {
         printf("\t\U0001F415");
     }
    printf("\t\t-\t");
    for(i=0;i<7;i++)
     {
         printf("\t\U0001F415");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==2)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         s_score=s_score+10;
     }
    printf("\n your score is %d\n",s_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(s_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<11;i++)
     {
         printf("\t\U0001F418");
     }
    printf("\t\t-\t");
    for(i=0;i<5;i++)
     {
         printf("\t\U0001F418");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==6)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         s_score=s_score+10;
     }
    printf("\n your score is %d\n",s_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(s_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<5;i++)
     {
         printf("\t\U0001F648");
     }
    printf("\t\t-\t");
    for(i=0;i<2;i++)
     {
         printf("\t\U0001F648");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==3)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         s_score=s_score+10;
     }
    printf("\n your score is %d\n",s_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(s_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<13;i++)
     {
         printf("\t\U0001F648");
     }
    printf("\t\t-\t");
    for(i=0;i<2;i++)
     {
         printf("\t\U0001F648");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==11)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         s_score=s_score+10;
     }
    printf("\n your score is %d\n",s_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(s_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<19;i++)
     {
         printf("\t\U0001F648");
     }
    printf("\t\t-\t");
    for(i=0;i<9;i++)
     {
         printf("\t\U0001F648");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==10)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         s_score=s_score+10;
     }
    printf("\n your score is %d\n",s_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(s_score);
            main();
    }
     printf("\t\t");
    for(i=0;i<18;i++)
     {
         printf("\t\U0001F648");
     }
    printf("\t\t-\t");
    for(i=0;i<13;i++)
     {
         printf("\t\U0001F648");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==5)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         s_score=s_score+10;
     }
    printf("\n your score is %d\n",s_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(s_score);
            main();
    }
     printf("\t\t");
    printf("\n your a_score is %d",s_score);
    insertatbegin(s_score);
}
void countinggame()
{int c_score=0,i,n;
    char c[1];
    // char str
    printf("\t\t\t\t\t\t*******************************\n\n");
    printf("\t\t\t\t\t\t\tWELCOME TO COUNTING GAME\n\n");
    printf("\t\t\t\t\t\tThe first place where thinking starts\n\n");
    printf("\t\t\t\t\t\t*******************************\n\n\n\n");
    printf("\n ENTER THE NUMBER OF FIGURES PRESENT BELOW\n\n\n\t\t");
   for(i=0;i<10;i++)
    {
        printf("\t\U0001F602");
    }
    printf("\nENTER YOUR ANSWER :");
    scanf("%d",&n);
    if(n==10)
    {
        printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
        c_score=c_score+10;
    }
    printf("\n your score is %d\n",c_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {insertatbegin(c_score);
        main();
        
    }
    printf("\t\t");
    for(i=0;i<7;i++)
    {
        printf("\t\U0001F600");
    }
    printf("\nENTER YOUR ANSWER :");
    scanf("%d",&n);
    if(n==7)
    {
        printf("\nCONGRATS YOU HAVE MADE IT\n");
        c_score=c_score+10;
    }
    printf("\n your score is %d\n",c_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    { insertatbegin(c_score);
        main();
    }
    printf("\t\t");
    for(i=0;i<13;i++)
    {
        printf("\t\U0001F605");
    }
    printf("\nENTER YOUR ANSWER :");
    scanf("%d",&n);
    if(n==13)
    {
        printf("\nCONGRATS YOU HAVE MADE IT\n");
        c_score=c_score+10;
    }
    printf("\n your score is %d\n",c_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(c_score);
            main();
    }
 //   printf("\n\n your score is %d",c_score);
    printf("\t\t");
    for(i=0;i<13;i++)
    {
        printf("\t\U0001F605");
    }
    printf("\nENTER YOUR ANSWER :");
    scanf("%d",&n);
    if(n==13)
    {
        printf("\nCONGRATS YOU HAVE MADE IT\n");
        c_score=c_score+10;
    }
    printf("\n your score is %d\n",c_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(c_score);
        main();
    }
    printf("\t\t");
    for(i=0;i<11;i++)
    {
        printf("\t\U0001F607");
    }
    printf("\nENTER YOUR ANSWER :");
    scanf("%d",&n);
    if(n==11)
    {
        printf("\nCONGRATS YOU HAVE MADE IT\n");
        c_score=c_score+10;
    }
    printf("\n your score is %d\n",c_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(c_score);
            main();
    }
    printf("\t\t");
   for(i=0;i<19;i++)
    {
        printf("\t\U0001F608");
    }
    printf("\nENTER YOUR ANSWER :");
    scanf("%d",&n);
    if(n==19)
    {
        printf("\nCONGRATS YOU HAVE MADE IT\n");
        c_score=c_score+10;
    }
    printf("\n your score is %d\n",c_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(c_score);
            main();
    }
    printf("\t\t");
    for(i=0;i<5;i++)
    {
        printf("\t\U0001F620");
    }
    printf("\nENTER YOUR ANSWER :");
    scanf("%d",&n);
    if(n==5)
    {
        printf("\nCONGRATS YOU HAVE MADE IT\n");
        c_score=c_score+10;
    }
    printf("\n your score is %d\n",c_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(c_score);
            main();
    }
    for(i=0;i<21;i++)
     {
         printf("\t\U0001F628");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==21)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         c_score=c_score+10;
     }
    printf("\n your score is %d\n",c_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(c_score);
            main();
    }
    for(i=0;i<16;i++)
     {
         printf("\t\U0001F631");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==16)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         c_score=c_score+10;
     }
    printf("\n your score is %d\n",c_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(c_score);
            main();
    }
    for(i=0;i<29;i++)
     {
         printf("\t\U0001F637");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==29)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         c_score=c_score+10;
     }
    printf("\n your score is %d\n",c_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {  insertatbegin(c_score);
        main();}
    for(i=0;i<12;i++)
     {
         printf("\t\U0001F640");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==12)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         c_score=c_score+10;
     }
    printf("\n your score is %d\n",c_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(c_score);
            main();
    }
    for(i=0;i<14;i++)
     {
         printf("\t\U0001F645");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==14)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         c_score=c_score+10;
     }
    printf("\n your score is %d\n",c_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(c_score);
            main();
    }
    for(i=0;i<19;i++)
     {
         printf("\t\U0001F646");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==9)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         c_score=c_score+10;
     }
    printf("\n your score is %d\n",c_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(c_score);
            main();
    }
    for(i=0;i<21;i++)
     {
         printf("\t\U0001F647");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==21)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         c_score=c_score+10;
    
     }
    printf("\n your score is %d\n",c_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(c_score);
            main();
    }
    for(i=0;i<24;i++)
     {
         printf("\t\U0001F648");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==24)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         c_score=c_score+10;
     }
    printf("\n your score is %d\n",c_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(c_score);
            main();
    }
    for(i=0;i<10;i++)
     {
         printf("\t\U0001F660");
     }
     printf("\nENTER YOUR ANSWER :");
     scanf("%d",&n);
     if(n==10)
     {
         printf("\nCONGRATS YOU HAVE MADE IT,LETS TRY FOR ANOTHER\n\n");
         c_score=c_score+10;
     }
    printf("\n your score is %d\n",c_score);
    printf("do you need to continue(Y/N)");
    scanf("%s",&c);
    if(c[0] =='N'||c[0]=='n')
    {
        insertatbegin(c_score);
            main();
    }
    printf("\n\n your score in counting game is %d",c_score);
    insertatbegin(c_score);
    
    
}

int main()
{int ch;
    printf("\n1.counting\n2.addition game\n3.subtraction game\n4.view your score\n5.exit\n");
    while(1)
    {
        printf("\n\n\n enter your choice");
        scanf("%d",&ch);
        switch(ch)
        {
            case 1:
                countinggame();
                break;
            case 2:
                addinggame();
                break;
            case 3:
                subtractinggame();
                break;
            case 4:
                viewyourscore();
                break;
            case 5:
                exit(0);
        }
        
    }
    
   
}
