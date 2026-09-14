# Ex.No:3(C)    STRING BUILDER IN JAVA

## AIM:
To Create a java program use replace() method replaces the given String from the specified beginIndex and endIndex and use stringbuilder

## ALGORITHM :
1.  Start the Program
2.	Import `Scanner` and define class `replace`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read a string `str` from user input
4.	Create a `StringBuilder` object `sb` initialized with `str`
5.	Use the `replace()` method to replace characters from index 1 to 3 with "Java"
6.	Print the modified string using `sb.toString()`
7.	End






## PROGRAM:
 ```
/*
Program to implement a String Builder using Java
Developed by: SARAVANA KUMAR S
RegisterNumber:  212224220090
*/
```

## Sourcecode.java:
```java
import java.util.Scanner;

public class StringLength {
    public static void main(String[] args) {
        // Create a Scanner object to read input
        Scanner scanner = new Scanner(System.in);

        String input = scanner.nextLine();

        // Create a StringBuilder object with the input string
        StringBuilder sb = new StringBuilder(input);

        // Get the length of the string
        int length = sb.length();

        // Output the result
        System.out.println("The size of the String is " + length);

        // Close the scanner
        scanner.close();
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/dccc1164-0826-4067-8155-f2ab1f8ab448)



## RESULT:
Thus the java program use replace() method replaces the given String from the specified beginIndex and endIndex and use stringbuilder was executed successfully.


