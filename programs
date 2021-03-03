#include<stdio.h>
#include<string.h>
#include<stdlib.h>
struct employee
{
    char id[5];
    char company[10];
};
typedef struct employee emp;
int main()
{
        emp e1[4];
        emp *e2=(emp *)malloc(sizeof(emp)*4);
    
        emp *temp=e2;
        for(int i=1; i<=4; i++)
        {
            scanf("%s",e2->id);
            scanf("%s",e2->company);
            e2++;
        }
        e2=temp;
        for(int i=1; i<=4; i++)
        {
            printf("[%s ,",e2->id);
            printf("%s]\n",e2->company);
            e2++;
            
        }    
}
 
