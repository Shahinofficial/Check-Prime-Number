#include <stdio.h>

#include <stdlib.h>

int main()
{

        int n,i;
        
    printf("Enter a number: \n");
    
    scanf("%d",&n);

    for(i=2;i<=n;i++)
    
    {
    
        if(n%i==0)
        
        {
        
            break;
            
        }
        
    }
    
    if(n==i)
    
    {
    
        printf("The number %d is prime.",n);
        
    }
    
    else{
    
        printf("The number %d is not prime.",n);
        
    }
    
    return 0;
}
