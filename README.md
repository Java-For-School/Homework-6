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
