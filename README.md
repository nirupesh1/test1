# test1
hello how are you doing
is everything fine with you how are you doing in the jenkins mode of execution
hello how are you doing
hello how are you doing
import java.util.Scanner;
class SwapNumbers
{
public static void main(String args[])
{
int z, y, temp;
System.out.println("Enter z and y");
Scanner sct = new Scanner(System.in);   //User inputs two numbers
z = sct.nextInt();   //User inputs two numbers
y = sct.nextInt();
System.out.println("Before Swapping\nz = "+z+"\ny = "+y);
temp = z;   //Swapping is done
z = y;
y = temp;
System.out.println("After Swapping\nz = "+z+"\ny = "+y);
}
}
