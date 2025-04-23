Sum of Array is a simple Java program that demonstrates how to calculate the sum of elements in an array using a for-each loop. The program initializes an array with a fixed set of integers and then computes and prints their sum.

Features
Iterates through an array of integers.

Calculates the total sum of the array elements.

Prints the result to the console.

Code Example
java
Copy
Edit
public class SumOfArray {

    public static void main(String[] args) {

        // Example array
        int[] numbers = {50, 60, 70, 80, 90};

        // Variable to store the sum
        int sum = 0;

        // for loop to the array to calculate sum
        for (int num : numbers) {
            sum += num;
        }

        // Print output
        System.out.println("The sum of the array elements is: " + sum);
    }
}
How to Run
Make sure you have Java installed on your system.

Save the file as SumOfArray.java.

Open your terminal or command prompt.

Compile the program:

nginx
Copy
Edit
javac SumOfArray.java
Run the program:

nginx
Copy
Edit
java SumOfArray
Output
python
Copy
Edit
The sum of the array elements is: 350
