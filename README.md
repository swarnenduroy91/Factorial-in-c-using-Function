# Factorial-in-c-using-Function
/*Finding Factorial Number*/

#include <stdio.h>

int factriol(int factriolNum){
    int i;
    int fact = 1;
    for(i=1;i<=factriolNum;i++){
        fact=fact*i;
    }
    return fact; 
}
int main() {
	//code
	int x=factriol(5);
	printf("%d",x);
	return 0;
}
