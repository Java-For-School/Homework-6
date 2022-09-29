# Assignment 6:

### Exercise: 40:

```java
import java.util.Scanner;

class Main {
    public static void main(String[] args) {
        int gcse, sat;
        Scanner scanner = new Scanner(System.in);
        
        gcse = scanner.nextInt();
        sat = scanner.nextInt();
        
        if (gcse < 90 && sat < 600) {
            System.out.println("You're a failure");
            return;
        }
        if (gcse < 90) {
            System.out.println("Pump those gsce's up");    
            return;
        }
        if (sat < 600) {
                System.out.println("Pump those sat's up");
                return;
        }
        System.out.println("You're goated");
    }
}
```
### Exercise 43:

```java
import java.util.Scanner;

class Main {
    public static void main(String[] args) {
        double zela1, zela2, zela3;
        Scanner scanner = new Scanner(System.in);
        
        zela1 = scanner.nextDouble();
        zela2 = scanner.nextDouble();
        zela3 = scanner.nextDouble();
    
        if (zela1 == zela2 && zela2 == zela3) System.out.println("All sides are equal");
        else if ((zela1 == zela2 && zela2 != zela3) || (zela1 == zela3 && zela2 != zela3) || (zela2 == zela3 && zela2 != zela1)) System.out.println("Two sides are equal");
        else System.out.println("Normal, disappointing triangle");
    }
}
```
