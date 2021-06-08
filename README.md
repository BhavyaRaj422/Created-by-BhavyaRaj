# Created-by-BhavyaRaj
import java.util.Scanner;
public class PrimeNUmber{
  public static void main(String[]args){
    Scanner scan = new Scanner(System.in);
    System.out.println("Enter a value");
    int num = scan.nextInt();
    boolean isPrime = true;
    for(int i =2;i<num;i++){
      if(num%1==0){
        isPrime = false;
        break;
      }
    }
    if(isPrime){
      System.out.println(num+"is a prime number");
      
    }else{
      System.out.println(num+"is not a prime number");
    }
  }
}
