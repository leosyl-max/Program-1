#include<stdio.h>
int main() {
      int n,i,j;
      printf("enter the size of the matrix:\n");
      scanf("%d", &n);
      for(i=1;i<=n;i++){
            for(j=1;j<=n;j++){
                    if (j==n-i+1 ||j==i){
                    printf("* ");
               } else {
               printf("  ");
               }
            }
                printf("\n");
            }
      return 0;
}
