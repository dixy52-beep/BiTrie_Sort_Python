# BiTrie Sort Python

## Description
BiTrie Sort is a sorting algorithm that efficiently organizes non-negative integers using a binary trie structure. It leverages an **iterative depth-first traversal** to ensure optimal performance and memory usage.

## Features
- **Efficient sorting** for non-negative integers.
- **Iterative depth-first traversal** to prevent recursion depth limitations.
- **Handles duplicate values** without unnecessary storage overhead.

## Installation
No external libraries are required. Simply clone the repository and run the Python script.

```sh
git clone https://github.com/dixy52-beep/BiTrie_Sort_Python.git
```

## Usage
Run the `BiTrie_Sort.py` script to execute various test cases.

```sh
python BiTrie_Sort.py
```

## Example
```python
from BiTrie_Sort import bitrie_sort

arr = [3, 1, 4, 1, 5, 9, 2, 6]
sorted_arr = bitrie_sort(arr)
print(sorted_arr)  # Output: [1, 1, 2, 3, 4, 5, 6, 9]
```

## Tests
The script includes predefined test cases to validate sorting accuracy and performance.

## License
This project is licensed under the MIT License. See `LICENSE.md` for details.

## Author
Created by **dixy52-beep**. Contributions are welcome!
