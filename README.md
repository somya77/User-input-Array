# User-input-Array
1-D array is formed and the values are user defined.
import java.util.Scanner;
class Test9
{
 public static void main(String args[])
{
  Scanner obj=new Scanner(System.in);
  int num[]=new int[3];
 System.out.println("Enter the values\n");
 for(int i=0;i<3;i++)
{
  num[i]=obj.nextInt();
}
System.out.println("The entered value is:");
for(int i=0;i<3;i++)
{
System.out.println(num[i]);
}
}
}
