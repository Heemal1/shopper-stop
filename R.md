# shopper-stop
// Online C compiler to run C program online
#include <stdio.h>
void func(int a,int b,int c){
    if(a>c){
        printf("0");
    }
    else if(a+b<=c){
        printf("2");
    }
    else{
        printf("1");
    }
}
int main() {int f;
    printf("enter the no");
    scanf("%d",&f);
   int i;
    for(i=0;i<f;i++){ int a,b,c;
        scanf("%d\t%d\t%d",&a,&b,&c);
        func(a,b,c);
    }
    
    return 0;
}
<!-- //output 
x ia amt y is bag z is budget
print 2 both 1 item 0 none
enter the no4 
1 2 3
2
10 12 13
1
23 1 22
0 23 1 63
23 1 63
2 -->
