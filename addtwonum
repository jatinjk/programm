#include <stdio.h>

struct print 
{
    int a;
    int b;
    int add;
};
struct print input()
{
    struct print p;
    printf ("enter two number : \n");
    scanf("%d",&p.a);
    scanf("%d",&p.b);
    return p;
}
struct print compute(struct print p)
{
    p.add = p.a+p.b;
    return p;
}
void output(struct print p)
{
    printf("%d",p.add);
}
int main()
{
    struct print p;
    p=input();
    p=compute(p);
    output(p);
}
