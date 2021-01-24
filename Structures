#include <stdio.h>
#include<conio.h>
#include<string.h>

struct employee{
    char name[20],dname[20];
    int no,s;
}e[20];

void display(struct employee e[20],int i)
{
    printf("Number\tName\t\tDepartment\tSalary\n");
    for (int j=0;j<i;j++)
    {
        printf("%d\t%s\t\t%s\t%d\n",e[j].no,e[j].name,e[j].dname,e[j].s);
    }
}
void main()
{
    struct employee e[20];
    int i=5;
    strcpy(e[0].name,"Anjali");
    strcpy(e[0].dname,"Coding  ");
    e[0].no=01;
    e[0].s=35000;

    strcpy(e[1].name,"Chirag");
    strcpy(e[1].dname,"Marketing");
    e[1].no=02;
    e[1].s=25000;

    strcpy(e[2].name,"Ayush ");
    strcpy(e[2].dname,"Hardware ");
    e[2].no=03;
    e[2].s=18000;

    strcpy(e[3].name,"Roshni");
    strcpy(e[3].dname,"HR      ");
    e[3].no=04;
    e[3].s=30000;

    strcpy(e[4].name,"Mohan ");
    strcpy(e[4].dname,"Coding  ");
    e[4].no=05;
    e[4].s=40000;

    display(e,i);
}
