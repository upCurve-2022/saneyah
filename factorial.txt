import java.util.*;
public class Factorial {
    public static void main(String arg[]){
        int fact=1;
        Scanner sc=new Scanner(System.in);
        System.out.print("Enter a number: ");
        int n=sc.nextInt();
        for(int i=1;i<=n;i++){
            fact=fact*i;
        }
        System.out.print("Factorial of "+n+" : "+fact);
    }
}
