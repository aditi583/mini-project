# mini-project
#include<stdio.h>
int main()
{
  int score = 0;
  char answer;
  
  printf("\nWELCOME TO THE QUIZ APP\n\n");
  printf("\n1.What is the father of C language?\n");	
  printf(" A.Harry\n B.Chaeles Babbage\n C.Dennis Ritchie\n D.James Gosling\n\n");
  printf("Enter Your Answer:");
  scanf(" %c",&answer);
  if(answer=='C'||answer=='c')
  {
  	score++;
  }
  printf("\n2.Which symbol is used at end of statement in C?\n");
  printf(" A.:\n B.;\n C.''\n D.,\n\n");
  printf("Enter Your Answer:");
  scanf(" %c",&answer);	
  if(answer=='B'||answer=='b')
  {
  	score++;
  }
  printf("\n3.Which header file is required to use the printf() function?\n");
  printf(" A. stdlib.\nB. conio.h\nC. stdio.h\nD. math.h\n\n");
  printf("Enter Your Answer:");
  scanf(" %c",&answer);	
  if(answer=='C'||answer=='c')
  {
  	score++;
 }
  
  printf("\n4.what is the size of int on most 32-bit system?\n");
  printf(" A.2 bytes\nB.4 bytes\nC.8 bytes\nD.1 bytes\n\n");
  printf("Enter Your Answer:");
  scanf(" %c",&answer);	
  if(answer=='B'||answer=='b')
  {
  	score++;
  }
  
   printf("\n5.Which keyword is used to define a constant in C?\n");	
  printf(" A.static\n B.final \n C.const\n D.define\n\n");
  printf("Enter Your Answer:");
  scanf(" %c",&answer);
  if(answer=='C'||answer=='c')
  {
  	score++;
  }
  printf("\n6.Which keyword is used to exit from a loop in C?\n");
  printf(" A.break\n B.stop\n C.exit\n D.end\n\n");
  printf("Enter Your Answer:");
  scanf(" %c",&answer);	
  if(answer=='A'||answer=='a')
  {
  	score++;
  }
     printf("\n7.What is the size of an empty structure in C?\n");	
  printf(" A.0 byte\n B.1 byte \n C.2 byte\n D.4 byte\n\n");
  printf("Enter Your Answer:");
  scanf(" %c",&answer);
  if(answer=='B'||answer=='b')
  {
  	score++;
  }
     printf("\n8.Which of the following statements about pointers in C is false?\n");	
  printf(" A.A NULL pointer points to no valid memory location.\n B.A pointer can be incremented to point to the next memory location. \n C.Dereferencing an u
  pointer is safe if it’s not NULL.\n D.A pointer stores the address of another variable.\n\n");
  printf("Enter Your Answer:");
  scanf(" %c",&answer);
  if(answer=='C'||answer=='c')
  {
  	score++;
  }
   printf("The Quiz is Completed\n");	
   printf("Your total correct answers:%d out of 8",score);
	
return 0;	
}
 
