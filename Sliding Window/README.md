
# 🪟 Sliding Window — DSA Guide (C++)

This folder contains problems and implementations based on the **Sliding Window technique** — an important pattern used to optimize array and string problems.

It is part of my **Data Structures & Algorithms practice repository**.

---

## 🔹 What is Sliding Window?

Sliding Window is a technique used to reduce time complexity when working with **contiguous subarrays or substrings**.

Instead of recalculating values for every window using nested loops:

```
O(n²)
```

We maintain a moving window and update results dynamically:

```
O(n)
```

This makes solutions significantly faster and interview-friendly.

---

## 🔹 Types of Sliding Window

### ✅ 1️⃣ Fixed Size Window

The window size `k` is constant.

#### Example Problems

* Maximum Sum Subarray of Size K
* First Negative Number in Every Window
* Average of Subarrays

#### Pattern

```cpp
while (right < n) {
    window += arr[right];

    if (window_size == k) {
        // process window
        window -= arr[left];
        left++;
    }

    right++;
}
```

---

### ✅ 2️⃣ Variable Size Window

Window size expands and shrinks based on conditions.

#### Example Problems

* Longest Substring Without Repeating Characters
* Minimum Window Substring
* Longest Repeating Character Replacement

#### Pattern

```cpp
while (right < n) {

    // expand window
    add(arr[right]);

    while (condition_breaks) {
        remove(arr[left]);
        left++;
    }

    update_answer();

    right++;
}
```

---

## 🔹 When to Use Sliding Window

Use this technique when the problem involves:

* Subarrays / Substrings
* Contiguous segments
* Maximum / Minimum length
* Count of valid windows
* Optimization from brute force

---

## 🔹 Complexity Advantage

| Approach       | Time Complexity |
| -------------- | --------------- |
| Brute Force    | O(n²)           |
| Sliding Window | O(n)            |

---

## 🔹 Topics Covered in This Folder

* Fixed window problems
* Variable window problems
* Frequency map windows
* Two-pointer optimization
* Interview patterns

---

## 🎯 Interview Tips

* Identify contiguous range problems
* Try replacing nested loops
* Maintain window state efficiently
* Use hashmap/set when needed
* Practice shrinking logic carefully

---

## 🚀 Goal

This folder documents my progress in mastering the Sliding Window pattern for:

* Coding interviews
* Competitive programming
* Strong DSA foundations

---

Happy Coding 🙂
