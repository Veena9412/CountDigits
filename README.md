# CountDigits
import java.util.*;
public class countdigits {
    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        int n,count =0;
        System.out.println("Enter n value");
        n=s.nextInt();
        while(n>0){
            n=n/10;
            count++;
        }
        System.out.println("No. of digits are " +count);
    }   

}
