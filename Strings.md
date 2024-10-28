

---

### 1. **String Slicing**

   - **Description**: Slicing allows you to extract a portion of a string by specifying a start, stop, and step index.
   - **Syntax**: `string[start:stop:step]`
     - **start**: Index where the slice begins (inclusive).
     - **stop**: Index where the slice ends (exclusive).
     - **step**: Interval between characters in the slice.

   - **Examples**:
     ```python
     text = "Hello, World!"
     print(text[0:5])        # Output: "Hello" (from index 0 to 4)
     print(text[7:])         # Output: "World!" (from index 7 to end)
     print(text[:5])         # Output: "Hello" (from start to index 4)
     print(text[-6:])        # Output: "World!" (using negative index)
     print(text[::2])        # Output: "Hlo ol!" (every 2nd character)
     ```

---

### 2. **`str.capitalize()`**
   - **Description**: Capitalizes the first character of the string.
   - **Usage**:
     ```python
     text = "hello"
     print(text.capitalize())  # Output: "Hello"
     ```

### 3. **`str.casefold()`**
   - **Description**: Returns a case-folded string, ideal for case-insensitive comparisons.
   - **Usage**:
     ```python
     text = "Hello"
     print(text.casefold())  # Output: "hello"
     ```

### 4. **`str.lower()`**
   - **Description**: Converts all characters in the string to lowercase.
   - **Usage**:
     ```python
     text = "HELLO"
     print(text.lower())  # Output: "hello"
     ```

### 5. **`str.upper()`**
   - **Description**: Converts all characters in the string to uppercase.
   - **Usage**:
     ```python
     text = "hello"
     print(text.upper())  # Output: "HELLO"
     ```

### 6. **`str.title()`**
   - **Description**: Converts the first character of each word to uppercase.
   - **Usage**:
     ```python
     text = "hello world"
     print(text.title())  # Output: "Hello World"
     ```

### 7. **`str.swapcase()`**
   - **Description**: Swaps uppercase characters to lowercase and vice versa.
   - **Usage**:
     ```python
     text = "Hello World"
     print(text.swapcase())  # Output: "hELLO wORLD"
     ```

### 8. **`str.find(substring)`**
   - **Description**: Returns the index of the first occurrence of `substring`, or `-1` if not found.
   - **Usage**:
     ```python
     text = "hello world"
     print(text.find("world"))  # Output: 6
     ```

### 9. **`str.replace(old, new)`**
   - **Description**: Replaces all occurrences of `old` with `new`.
   - **Usage**:
     ```python
     text = "hello world"
     print(text.replace("world", "Python"))  # Output: "hello Python"
     ```

### 10. **`str.split(separator)`**
   - **Description**: Splits the string into a list of substrings, based on `separator`.
   - **Usage**:
     ```python
     text = "hello world"
     print(text.split())  # Output: ["hello", "world"]
     ```

### 11. **`str.join(iterable)`**
   - **Description**: Joins elements of `iterable` (like a list) with the string as a separator.
   - **Usage**:
     ```python
     words = ["hello", "world"]
     print(" ".join(words))  # Output: "hello world"
     ```

### 12. **`str.strip()`**
   - **Description**: Removes leading and trailing whitespace from the string.
   - **Usage**:
     ```python
     text = "  hello world  "
     print(text.strip())  # Output: "hello world"
     ```

### 13. **`str.startswith(prefix)`**
   - **Description**: Checks if the string starts with the specified `prefix`.
   - **Usage**:
     ```python
     text = "hello world"
     print(text.startswith("hello"))  # Output: True
     ```

### 14. **`str.endswith(suffix)`**
   - **Description**: Checks if the string ends with the specified `suffix`.
   - **Usage**:
     ```python
     text = "hello world"
     print(text.endswith("world"))  # Output: True
     ```

### 15. **`str.count(substring)`**
   - **Description**: Counts the occurrences of `substring` in the string.
   - **Usage**:
     ```python
     text = "hello hello world"
     print(text.count("hello"))  # Output: 2
     ```

### 16. **`str.isdigit()`**
   - **Description**: Checks if all characters in the string are digits.
   - **Usage**:
     ```python
     text = "1234"
     print(text.isdigit())  # Output: True
     ```

### 17. **`str.isalpha()`**
   - **Description**: Checks if all characters in the string are alphabetic.
   - **Usage**:
     ```python
     text = "hello"
     print(text.isalpha())  # Output: True
     ```

### 18. **`str.isalnum()`**
   - **Description**: Checks if all characters in the string are alphanumeric (letters or numbers).
   - **Usage**:
     ```python
     text = "hello123"
     print(text.isalnum())  # Output: True
     ```

### 19. **`str.isupper()`**
   - **Description**: Checks if all alphabetic characters in the string are uppercase.
   - **Usage**:
     ```python
     text = "HELLO"
     print(text.isupper())  # Output: True
     ```

### 20. **`str.islower()`**
   - **Description**: Checks if all alphabetic characters in the string are lowercase.
   - **Usage**:
     ```python
     text = "hello"
     print(text.islower())  # Output: True
     ```

### 21. **`str.center(width, fillchar=' ')`**
   - **Description**: Centers the string within a given `width`, padding it with `fillchar` (default is a space).
   - **Usage**:
     ```python
     text = "hello"
     print(text.center(10, "-"))  # Output: "--hello---"
     ```

---

This cheat sheet provides a handy reference to Python’s string functions, including slicing techniques and their various applications.
