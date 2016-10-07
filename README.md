import java.util.*;
import java.io.*;
class Reversestr
{
 public static void main(String args[])
 {
  System.out.println("enter the string to be reversed");
  Scanner s=new Scanner(System.in);
  String s1=s.next();
  for(int i=s1.length()-1;i>=0;i--)
  {
 	System.out.println(s1.charAt(i));
  }
 }
}
