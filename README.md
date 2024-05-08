import java.util.*;
public class javacode {
    public static void main(String[]args){
        Scanner scan =new Scanner(System.in);
        System.out.println("Enter a Number");
        int num=scan.nextInt();
        if (num % 2 ==0){
            System.out.println("Even");
         }
         else {
            System.out.println("Odd");
         }
    }
    
}
