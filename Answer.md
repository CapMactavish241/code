[1.](#one)
```java
import java.util.Scanner;
public class Main{
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
