# OOP2026
### HomeWork1
```java
public class hw1 {
    public static void main(String[] args) {
        for (int i = 1; i <= 4; i++) {
            // Pattern 1: left-aligned increasing triangle
            for (int j = 1; j <= i; j++) {
                System.out.print("#");
            }
            for (int j = 1; j <= 7 - i; j++) {
                System.out.print(" ");
            }

            // Pattern 2: right-aligned decreasing triangle
            for (int j = 1; j < i; j++) {
                System.out.print(" ");
            }
            for (int j = 1; j <= 5 - i; j++) {
                System.out.print("#");
            }
            for (int j = 1; j <= 3; j++) {
                System.out.print(" ");
            }

            // Pattern 3: left-aligned increasing triangle
            for (int j = 1; j <= i; j++) {
                System.out.print("#");
            }
            for (int j = 1; j <= 7 - i; j++) {
                System.out.print(" ");
            }

            // Pattern 4: right-aligned decreasing triangle
            for (int j = 1; j < i; j++) {
                System.out.print(" ");
            }
            for (int j = 1; j <= 5 - i; j++) {
                System.out.print("#");
            }
            System.out.println();
        }
    }
}

### HomeWork2
```java
