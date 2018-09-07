#include <stdio.h>

struct print 
{
    char a[20];
};
struct print input()
{
    struct print p;
    printf ("enter the name : \n");
    gets(p.a);
    return p;
}
struct print compute(struct print p)
{
    return p;
}
void output(struct print p)
{
    printf("%s",p.a);
}
int main()
{
    struct print p;
    p=input();
    p=compute(p);
    output(p);
}
