# Maximum Subarray and Subsequence Sum

A Java 8 implementation to find the maximum possible sums for a **contiguous subarray** and a **non-contiguous subsequence** from a given integer array.

##  Overview
This solution addresses the classic algorithmic challenge of finding the highest potential sums under two different constraints:
* **Subarray:** Must be a continuous segment (Solved using **Kadane's Algorithm**).
* **Subsequence:** Can be any subset of elements, maintaining at least one element.

## Logic & Complexity
* **Time Complexity:** $O(n)$ — The array is traversed only once.
* **Space Complexity:** $O(1)$ — No additional data structures are required.
* **Edge Cases:** Correcty handles arrays containing only negative integers by selecting the single largest element.

## Usage
1. Ensure you have **Java 8** or higher installed.
2. Compile the solution: `javac Solution.java`
3. Run the solution: `java Solution`

## License
This project is open-source and available under the [MIT License](LICENSE).
