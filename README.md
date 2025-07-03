# mini-project
#include<stdio.h>
<br>
int main()
<br>
{
<br>
  int score = 0;
  <br>
  char answer;
  <br>
  
  printf("\nWELCOME TO THE QUIZ APP\n\n");
  <br>
  printf("\n1.What is the father of C language?\n");
  <br>
  printf(" A.Harry\n B.Chaeles Babbage\n C.Dennis Ritchie\n D.James Gosling\n\n");
  <br>
  printf("Enter Your Answer:");
  <br>
  scanf(" %c",&answer);
  <br>
  if(answer=='C'||answer=='c')
  <br>
  {
  <br>
  	score++;
   <br>
  }
  <br>
  printf("\n2.Which symbol is used at end of statement in C?\n");
  <br>
  printf(" A.:\n B.;\n C.''\n D.,\n\n");
  <br>
  printf("Enter Your Answer:");
  <br>
  scanf(" %c",&answer);	
  <br>
  if(answer=='B'||answer=='b')
  <br>
  {
  <br>
  	score++;
   <br>
  }
  <br>
  printf("\n3.Which header file is required to use the printf() function?\n");
  <br>
  printf(" A. stdlib.\nB. conio.h\nC. stdio.h\nD. math.h\n\n");
  <br>
  printf("Enter Your Answer:");
  <br>
  scanf(" %c",&answer);	
  <br>
  if(answer=='C'||answer=='c')
  <br>
  {
  <br>
  	score++;
   <br>
 }
 <br>
  
  printf("\n4.what is the size of int on most 32-bit system?\n");
  <br>
  printf(" A.2 bytes\nB.4 bytes\nC.8 bytes\nD.1 bytes\n\n");
  <br>
  printf("Enter Your Answer:");
  <br>
  scanf(" %c",&answer);	
  <br>
  if(answer=='B'||answer=='b')
  <br>
  {
  <br>
  	score++;
   <br>
  }
  <br>
  
   printf("\n5.Which keyword is used to define a constant in C?\n");	
   <br>
  printf(" A.static\n B.final \n C.const\n D.define\n\n");
  <br>
  printf("Enter Your Answer:");
  <br>
  scanf(" %c",&answer);
  <br>
  if(answer=='C'||answer=='c')
  <br>
  {
  <br>
  	score++;
   <br>
  }
  <br>
  printf("\n6.Which keyword is used to exit from a loop in C?\n");
  <br>
  printf(" A.break\n B.stop\n C.exit\n D.end\n\n");
  <br>
  printf("Enter Your Answer:");
  <br>
  scanf(" %c",&answer);	
  <br>
  if(answer=='A'||answer=='a')
  <br>
  {
  <br>
  	score++;
   <br>
  }
  <br>
     printf("\n7.What is the size of an empty structure in C?\n");
     <br>
  printf(" A.0 byte\n B.1 byte \n C.2 byte\n D.4 byte\n\n");
  <br>
  printf("Enter Your Answer:");
  <br>
  scanf(" %c",&answer);
  <br>
  if(answer=='B'||answer=='b')
  <br>
  {
  <br>
  	score++;
   <br>
  }
  <br>
     printf("\n8.Which of the following statements about pointers in C is false?\n");	
     <br>
  printf(" A.A NULL pointer points to no valid memory location.\n B.A pointer can be incremented to point to the next memory location. \n C.Dereferencing an upointer is safe if it’s not NULL.\n D.A pointer stores the address of another variable.\n\n");
  <br>
  printf("Enter Your Answer:");
  <br>
  scanf(" %c",&answer);
  <br>
  if(answer=='C'||answer=='c')
  <br>
  {
  <br>
  	score++;
   <br>
  }
  <br>
   printf("The Quiz is Completed\n");	
   <br>
   printf("Your total correct answers:%d out of 8",score);
   <br>
	
return 0;	
<br>
}
<br>
 
