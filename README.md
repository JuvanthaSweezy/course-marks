/*
 * Juvantha crawford
 */ 
  
import java.util.*;

public class coursemarks
{
public static void main(String[] args)
{
Scanner myInput = new Scanner(System.in);
//Deteriming variables
System.out.println("Please enter three numbers");

double num1 = myInput.nextDouble();

double num2 = myInput.nextDouble();

double num3 = myInput.nextDouble();

double num4 = myInput.nextDouble();

double average = ((num1 + num2 + num3 + num4) / 4);
//Output
System.out.println(average);

}//end main
}//end class
