# Test
import java.util.Scanner;
public class Main {
  public static void main(String[] args) {
   Scanner in=new Scanner (System.in);
    System.out.println("Enter the number:");
    double x=in.nextInt();
   System.out.println("Enter the os:");
    double y=in.nextInt();
    double res=1;
    for (int i=1;i<=y;i++){
     res*=x;}
      System.out.println("the result is:"+res);
    
    
    
    }}
