#include <stdio.h>
#include <conio.h>
void main()
{
 // Declare variables
 char name[50];
 int member_number;
 int age;
 float annual_fee;
 clrscr();
 // Input Section
 printf("=== Library Membership Registration ===\n");
 printf("Enter Member's Full Name: ");
 // Read a full name including spaces
 scanf(" %49[^\n]", name);
 printf("Enter Membership Number: ");
 scanf("%d", &member_number);
 printf("Enter Age: ");
 scanf("%d", &age);
 printf("Enter Annual Fee (in rupees): ");
 scanf("%f", &annual_fee);
 // Output Section
 printf("\n----------------------------------");
 printf("\n LIBRARY MEMBERSHIP REPORT");
 printf("\n----------------------------------");
 printf("\n Member Name : %s", name);
 printf("\n Membership Number : %d", member_number);
 printf("\n Age : %d", age);
 printf("\n Annual Fee : Rs. %.2f", annual_fee);
 printf("\n----------------------------------\n");
getch();
}