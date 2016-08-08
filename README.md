# kenta
#inclide<studio.h>
int main(void)
{
int no
int ans
printf("0~9の整数をあててください\n\n");
do{
printf("いくつかな")；
scanf("%d",&no);
if(no>ans)
printf("\aはもっと小さいよ\n");
else if (no<ans )
printf("\aはもっと大きいよ\n");
}while(no!=ans);
printf("正解です");
return 0
}
