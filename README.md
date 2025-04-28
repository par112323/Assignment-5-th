import java.util.Arrays;

public class AlphabeticalSort {
    public static void main(String[] args) {
        // Array of strings
        String[] words = { "banana", "apple", "cherry", "mango", "blueberry" };

        // Display the original array
        System.out.println("Original array:");
        for (String word : words) {
            System.out.println(word);
        }

        // Sort the array
        Arrays.sort(words);

        // Display the sorted array
        System.out.println("\nSorted array:");
        for (String word
