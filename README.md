#include<stdio.h> 
 void main() 
 { 
         int a,b,c; 
         scanf("%d %d %d",&a,&b,&c); 
         if(a>b&&a>c) 
         { 
             printf("A is the Biggest Number"); 
         } 
         else if(a<b&&b>c) 
         { 
             printf("B is the Biggest Number"); 
         } 
         else 
         { 
             printf("C is the Biggest Number"); 
         } 
  
 }









<stdio.h> 
 void main() 
 { 
 int n,i; 
 scanf("%d",&n); 
 i=1; 
 while(i<11) 
 { 
     printf("%d X %d=%d\n",n,i,n*i); 
     i++; 
 } 
 }




#include<stdio.h> 
 void main() 
 { 
    char hey; 
    scanf("%c",&hey); 
    switch(hey) 
    { 
        case 'a': 
        printf("IT IS AN VOWEL"); 
        break; 
        case 'e': 
        printf("IT IS AN VOWEL"); 
        break; 
        case 'i': 
        printf("IT IS AN VOWEL"); 
        break; 
        case 'o': 
        printf("IT IS AN VOWEL"); 
        break; 
        case 'u': 
        printf("IT IS AN VOWEL"); 
        break; 
        default: 
        printf("IT IS NOT AN VOWEL"); 
    } 
  
 }













