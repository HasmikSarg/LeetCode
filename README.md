# LeetCode Solutions in Java

This repo has my solutions to various LeetCode problems, all written in Java. Each problem lives in its own folder with the Java solution file and a README explaining what the problem is about.

---

## ✅ Solved Problems

### 1. 53. Maximum Subarray  
**Difficulty:** Medium

Given an integer array `nums`, find the subarray with the largest sum and return that sum.

**Example:**
```
Input: nums = [-2,1,-3,4,-1,2,1,-5,4]
Output: 6
Explanation: The subarray [4,-1,2,1] has the largest sum of 6.
```

---

### 2. 121. Best Time to Buy and Sell Stock  
**Difficulty:** Easy

You're given an array `prices` where `prices[i]` is the price of a stock on the *i*-th day. You want to maximize your profit by picking one day to buy and a different future day to sell. Return the max profit you can get. If you can't make any profit, return 0.

**Example:**
```
Input: prices = [7,1,5,3,6,4]
Output: 5
Explanation: Buy on day 2 (price = 1) and sell on day 5 (price = 6), profit = 6-1 = 5.
```

---

### 3. 152. Maximum Product Subarray  
**Difficulty:** Medium

Given an integer array `nums`, find a subarray that has the largest product and return that product. The test cases guarantee the answer fits in a 32-bit integer.

**Example:**
```
Input: nums = [2,3,-2,4]
Output: 6
Explanation: [2,3] has the largest product of 6.
```

---

## 🛠️ How to Use

To compile and run any of these Java solutions:

### 1. Clone the repo:
```bash
git clone <YOUR_REPO_URL>
```

### 2. Go to the problem folder you want:  
Example:
```bash
cd LeetCode-0aa310c2618bc02fc1237c4e2020412914899540/0053-maximum-subarray
```

### 3. Compile the Java file:
```bash
javac Solution.java
```

### 4. Run the solution:  
These solutions are meant to run on LeetCode's platform. To test them locally, you'll need to add a `main` method to the `Solution` class with some test cases.

**Example `main` for Maximum Subarray:**
```java
public static void main(String[] args) {
    Solution sol = new Solution();
    int[] nums1 = {-2,1,-3,4,-1,2,1,-5,4};
    System.out.println("Max Subarray Sum for [-2,1,-3,4,-1,2,1,-5,4]: " + sol.maxSubArray(nums1)); // Expected: 6
    
    int[] nums2 = {1};
    System.out.println("Max Subarray Sum for [1]: " + sol.maxSubArray(nums2)); // Expected: 1
}
```

### 5. After adding the `main` method, compile and run:
```bash
javac Solution.java
java Solution
```

---

## 📄 License

This project is under the MIT License. Check the `LICENSE` file for details.

---

### MIT License
```
Copyright (c) 2025 Helena

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
