#include <stdio.h>

struct sum  {
    int arr[100];
    int size;
    int add;
};

struct sum input()  {
    struct sum k;
    printf("Total no. of elements : \n");
    scanf("%d",&k.size);
    printf("Enter %d elements \n",k.size);
    for (int i = 0; i < k.size; ++i) {
        scanf("%d",&k.arr[i]);
    }
    return k;
}

struct sum compute(struct sum k)    {
    k.add = 0;
    for (int i = 0; i < k.size; ++i) {
        k.add = k.add + k.arr[i];
    }
    return k;
}

struct sum output(struct sum k) {
    printf("Result : %d",k.add);
}

int main() {
    struct sum structSum;
    structSum = input();
    structSum = compute(structSum);
    output(structSum);
    return 0;
}
