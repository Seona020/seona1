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


2+1+3+4 = 10     + 2 =12 
나머지 3시간???????
