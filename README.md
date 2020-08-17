# java-min-converting
Min converting to years and days
import java.util.Scanner;
class Main
 {
   public static void main(String args[])
   {
     Scanner sc= new Scanner(System.in);
    // System.out.print("Enter hours- ");
    // int a= sc.nextInt();
     System.out.print("Enter minutes- ");
     int m= sc.nextInt();
     int x=m/1440;
     int y=x/365;
     int d=x%365;
    System.out.println(m+" minutes is approximately "+y+" years and "+d+" days");
   }
 }
