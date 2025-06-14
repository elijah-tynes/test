# testing.java

## Overview
`testing.java` is a simple Java file containing utility methods for string manipulation. It features a basic class with a main method and two static utility methods.

## Features
- **Reverse String**: Reverse the contents of a `String`.
- **String to Char Array**: Convert a `String` into a character array.

## Code Structure
```
public class testing {
    public static void main(String[] args) {
        String potato = "";
        String john = "";
    }

    public static String reverseString(String input) {
        return new StringBuilder(input).reverse().toString();
    }

    public static char[] stringToCharArray(String input) {
        return input.toCharArray();
    }
}
```

## Usage
You can use the static methods without creating an instance of the class:
```java
String reversed = testing.reverseString("hello"); // Output: "olleh"
char[] chars = testing.stringToCharArray("hello"); // Output: ['h', 'e', 'l', 'l', 'o']
```

## Author
Auto-generated README
