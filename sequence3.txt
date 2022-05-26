import java.util.*;
public class Sequence13 {
    public static void main(String arg[]){
        int product;
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the limit: ");
        int limit=sc.nextInt();
        for(int i=1;i<=limit;i++){
            product=1;
            for(int j=1;j<=i;j++){
                product=product*i;
            }
            if(i==1)
                System.out.print(product);
            else
                System.out.print(","+product);
        }
    }
}
