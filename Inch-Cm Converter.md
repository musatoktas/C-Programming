 

    #include <stdio.h>
    #include <stdlib.h>
    
    int main()
    {
    int selection;
    float centimeter;
    float inches;
    float outcome;
    
    
    printf("1 for cm to inch convertion\n");
    printf("2 for inch to cm convertion\n");
    scanf("%d", &selection);
    
    if(selection == 1){
    	printf("Insert the cm value:\n");
    	scanf("%f", &centimeter);
    	outcome = centimeter/2.4;
    	printf("The result is: %f inch\n", outcome);
    }
	
    else if (selection == 2){
    	printf("Insert the inch value:\n");
    	scanf("%f", &inches);
    	outcome = inches*2.4;
    	printf("The result is: %f cm\n", outcome);
    }
    
	else{
    	printf("Invalid Entry!\n");
    }
    
    return 0;
    }
    