# Unique Element Finder in C++

## 📝 Project Description
This repository contains an optimized C++ solution designed to filter and extract unique string elements from a given sequence. The program processes the elements in reverse order and ensures that each string is printed only once, eliminating any duplicates efficiently using hashing.

## 🚀 Performance Optimizations
* **Fast I/O Operations:** Utilizes `ios_base::sync_with_stdio(false);` and `cin.tie(nullptr);` to untie C++ streams from C standard streams, significantly reducing input/output latency for large datasets.
* **Efficient Lookups:** Implements an `unordered_map` (hash table) to achieve an average time complexity of $O(1)$ for element lookup and insertion.

## 🛠️ How It Works
1. The user specifies the total number of strings ($N$).
2. The program stores the sequence in a `std::vector`.
3. It iterates through the vector in reverse order ($N-1$ down to $0$).
4. A hash map tracks previously seen items. If an item has already been printed, the script skips it; otherwise, it outputs the unique string.

## 💻 Technical Details
* **Language:** C++17 or higher
* **Standard Libraries Used:** `<vector>`, `<string>`, `<unordered_map>`, `<iostream>`
