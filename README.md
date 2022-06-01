#pragma warning(disable:4996)
#include <stdio.h>

int main()
{ 
    char a, b;
    
    printf("좋아하는 알파벳: ");
    scanf("%c", &a);
    printf("좋아하는 알파벳: ");
    scanf("%c", &b);

    FILE* fp;
    fp = fopen("alpha.txt", "w");
    if (fp == NULL) { printf("파일 열기 실패\n"); return 0; }
    for (int i = 0; i < 10; i++) {
        fputc(a, fp);
        fputc(b, fp);
        fputc('\n', fp);
    }
    fclose(fp);
    printf("잘했어요!!");
    return 0;
}


#pragma warning(disable:4996)
#include <stdio.h>
#include <stdlib.h>
int main() { 
    long longfactorial(int n) { 
        if (n <= 1) return 1; 
        else return n * factorial(n - 1);  }
    int main() {
        int arr[5] = { 2, 3, 5, 10, 15 }; long longfarr[5]; long long* p = farr; for (int i = 0; i < 5; i++) {
            *p = factorial(arr[i]); p++;
    
    for (i = 0; i < 10; i++) {
        fputc(a, fp);
        fputc(b, fp);
        fputc('\n', fp);
    }
    fclose(fp);
    printf("잘했어요!!");
    return 0;
}
