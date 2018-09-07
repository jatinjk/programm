#include <stdio.h>

struct print 
{
    int a;
};
struct print input()
{
    struct print p;
    printf ("enter the number : \n");
    scanf("%d",&p.a);
    return p;
}
struct print compute(struct print p)
{
    return p;
}
void output(struct print p)
{
    printf("%d",p.a);
}
int main()
{
    struct print p;
    p=input();
    p=compute(p);
    output(p);
}
