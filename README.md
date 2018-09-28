#include <stdio.h>
 
void main()
{
    int i, tram, chuc, donvi;
    printf("Nhap chu so tu 100 - 999: ");
    scanf("%d", &i);
    if(i > 999 || i < 100)
    {
        printf("Nhap sai chu so");
    }
    else
    {
         
    donvi = i%10;
    chuc = (i/10)%10;
    tram = i/100;
         
        printf("\n So hang tram: %d", tram);
        printf("\n So hang chuc: %d", chuc);
        printf("\n So hang don vi: %d \n", donvi);      
    }
    getch();
}
