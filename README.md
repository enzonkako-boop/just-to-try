#include <stdio.h>
#include <stdlib.h>

/* run this program using the console pauser or add your own getch, system("pause") or input loop */

int main(int argc, char *argv[]) { char region[50];
     char full_name[100];     /* 1.  Full Name             */
     int  age;                /* 2.  Age (   */
     char gender[20];         /* 3.  Gender                */
     char birth_date[20];     /* 4.  Date of Birth         */
     char nationality[50];    /* 5.  Nationality           */ 
	 char region of origin[50]       /* 6.  Region of Origin      */
     char current city[50];           /* 7.  Current City          */
     char address[100];       /* 8.  Residential Address   */
     char phone[20];          /* 9.  Telephone Number      */
     char email[100];         /* 10. Email Address         */
     char education[50];      /* 11. Highest Level of Education */
     char hobbies[100];       /* 12. Hobbies               */
	 
	 
	 printf("Enter your full name: ");
     scanf("%s\n", full_name);

     printf("Enter your age: ");
     scanf("%d\n", &age);              

    printf("Enter your gender: ");
    scanf("%s\n", gender);

    printf("Enter your date of birth (DD/MM/YYYY): ");
    scanf("%s\n", birth_date);

    printf("Enter your nationality: ");
    scanf("%s\n", nationality);

    printf("Enter your region of origin: ");
    scanf("%s\n", region);

    printf("Enter your current city: ");
    scanf("%s\n", city);

    printf("Enter your residential address: ");
    scanf("%s\n", address);

    printf("Enter your telephone number: ");
    scanf("%s\n", phone);

    printf("Enter your email address: ");
    scanf("%s\n", email);

    printf("Enter your highest level of education: ");
    scanf("%s\n", education);

    printf("Enter your hobbies: ");
    scanf("%s\n", hobbies);
	
     return 0;
     }
	
	return 0;
}
