import java.util.Scanner;

public class Fibonacci {

    // Method to print Fibonacci series up to n terms
    public static void printFibonacci(int n) {
        long first = 0, second = 1;

        System.out.print("Fibonacci Series up to " + n + " terms: ");

        // For the first two terms, simply print 0 and 1
        if (n >= 1) {
            System.out.print(first + " ");
        }
        if (n >= 2) {
            System.out.print(second + " ");
        }

        // For the remaining terms, calculate the Fibonacci numbers
        for (int i = 3; i <= n; i++) {
            long nextTerm = first + second;
            System.out.print(nextTerm + " ");
            first = second;   // Move the second number to the first position
            second = nextTerm; // Move the next number to the second position
        }

        System.out.println(); // For a new line after the series
    }

    public static void main(String[] args) {
        // Create a Scanner object for user input
        Scanner scanner = new Scanner(System.in);

        // Take input from the user
        System.out.print("Enter the number of terms in Fibonacci series: ");
        int terms = scanner.nextInt();

        // Print the Fibonacci series
        printFibonacci(terms);

        // Close the scanner to prevent memory leak
        scanner.close();
    }
}
