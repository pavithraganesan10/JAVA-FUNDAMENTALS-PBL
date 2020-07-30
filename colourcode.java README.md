# JAVA-FUNDAMENTALS-PBL
import java.util.Scanner;
public class colorcode{ 
public static void main(String[] args) {
Scanner myObj = new Scanner(System.in); 
char ch = myObj.next().charAt(0); 
if(ch=='R') 
System.out.println("Red"); 
else if(ch=='G') 
System.out.println("Green");
else if(ch==('O'))
System.out.println("Orange"); 
else if(ch==('Y'))
System.out.println("Yellow");
else if(ch==('W')) 
System.out.println("White");
else if(ch==('B'))
System.out.println("Blue");
else 
System.out.printf("Invalid Code"); 
}
}
