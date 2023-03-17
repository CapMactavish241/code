[1.](#one)
```java
import java.util.Scanner;
public class Main{
   static Scanner sc = new Scanner(System.in);
   public static void main(String[] args){
      System.out.println("Enter values for x and n");
      int x = sc.nextInt(), n = sc.nextInt();
      double sum = 0;
      for(int i = 1; i<=n; i++){
         double factorial = 1;
         for(int j =1; j<=i+1;j++) factorial *= j;
         sum += x*1.00/factorial;
      }
      System.out.println("Sum of series="+sum);
   }
}   
```
[2.](#two)
```java
import java.util.Scanner;

public class Investment {
    static Scanner sc = new Scanner(System.in);

    public static void main(String[] args){
        int n;
        do {
            System.out.println("Enter number of years:");
            n = sc.nextInt();
        } while (n>3 || n<1);
        double r;
        if(n == 1) r = 8;
        else if(n == 2) r = 8.5;
        else r = 9;
        System.out.println("Enter amount invested: ");
        double ai = sc.nextDouble();
        double ad = (ai * Math.pow((1+r/100),n));
        System.out.println("Amount after " + n + " years: " + ad);
    }
}
```
