#include<stdio.h>
#include<stdlib.h>
int main(){
    char a[50];//assigning character//

	printf("enter string \n");//enter the word to check palindrome or not//
    fflush(stdout);
    gets(a);
    char b[50];//assigning second character//
        strcpy(b,a);//copying the one character to another//
    strrev(a);//reversing the first character  //

if (strcmp(b,a)==0){//comparing the both character//
	printf(" entered word is palindrome \n");//it will recognize the word if its palindrome//
}
else{
	printf(" entered word is not a palindrome \n");//if its not a palindrome //
	return 0;
}

}

