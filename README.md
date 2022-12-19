# Even-Odd-Software
Program

import java.util.Scanner;
class EvenOdd{
  public static void main(String args []){
  Scanner se=new Scanner(System.in);
  System.out.println("Enter a Number");
  int n = se.nextInt();
  if(n%2==0){
  System.out.println(n+"is even");
  }
  else{
  System.out.println(n+"is odd");
      }
  }
}
