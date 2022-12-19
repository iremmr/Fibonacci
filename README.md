# Fibonacci
```
import java.util.Scanner;

public class Fibonacci {
    public static void main(String[] args) {
        int a = 1, b = 1, d;
        int c;


        Scanner input = new Scanner(System.in);
        System.out.print("Eleman sayısını giriniz:");
        d = input.nextInt();
        System.out.println(a);
        System.out.println(b);

        for (int i = 1; i <= d - 2; i++) {
            c = a + b;
            a = b;
            b = c;
            System.out.println(c);

        }

    }
}
```
[Patika.dev](https://app.patika.dev/iremr)
