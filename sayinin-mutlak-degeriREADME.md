# kosullu-ifadeler
#include <stdio.h>
int main(){
int sayi;
printf("bir sayi giriniz:");
scanf("%d",&sayi);

if(sayi < 0){
sayi = -1 * sayi;
printf("girilen sayinin degeri: %d\n",sayi)
}
else{
printf("girilen sayinin degeri:%d\n",sayi);
}


return 0;
}
