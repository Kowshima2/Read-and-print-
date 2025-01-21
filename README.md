# Read-and-print-
import java.util.Scanner;

public class ReadAndPrint {
    public static void main(String[] args) 
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter something: ");
        String input = scanner.nextLine(); // Read input as a string

     
        System.out.println("You entered: " + input);

       
        scanner.close();
    }
}

Output 
Enter something: Hello, Java!
You entered: Hello, Java!
