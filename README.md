# Binary Search in C

This project contains a simple implementation of the **Binary Search algorithm** using the C programming language.

## 📌 About the Project

Binary Search is an efficient searching algorithm used to find an element in a **sorted array**.

The algorithm repeatedly divides the search range into two halves until the target element is found or the search range becomes empty.

## 💻 Language

* C

## 🔍 Example

Given the sorted array:

```text
2 3 4 10 40
```

Target element:

```text
10
```

Output:

```text
Element found at index 3
```

## ⚙️ How It Works

1. Set `low` to the first index.
2. Set `high` to the last index.
3. Calculate the middle index.
4. Compare the middle element with the target.
5. If the target is greater, search the right half.
6. If the target is smaller, search the left half.
7. Repeat until the element is found.

## ⏱️ Time Complexity

* **Best Case:** O(1)
* **Average Case:** O(log n)
* **Worst Case:** O(log n)

## 💾 Space Complexity

* **O(1)**

## ▶️ How to Run

Compile the program using GCC:

```bash
gcc binary_search.c -o binary_search
```

Run the program:

```bash
./binary_search
```

## 📤 Output

```text
Element found at index 3
```

## 👨‍💻 Author

Created as a basic C programming and Data Structures practice project.

