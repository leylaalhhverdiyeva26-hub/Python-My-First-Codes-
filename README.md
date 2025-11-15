# Python-My-First-Codes-
All the assignments and small projects I wrote during my Python lessons.
## 📝 Lesson 1: Strings and Working with Them

This is one of the first lessons where I started learning Python in this repository, demonstrating how to work with **string** data types.

Here are the topics I learned in practice with these small code snippets:

### What Did I Learn?

1.  **Concatenating Strings:**
    * I learned how to take a few string variables (`mesaj`, `mesaj2`) and turn them into a single sentence using the `+` operator.
2.  **"Navigating" Within a String:**
    * **Indexing:** I learned how to extract any character of a string by its position (e.g., `mesaj[0:4]`).
    * **Reverse Indexing:** I practiced counting backward from the end of the string (e.g., `mesaj[-2]` to get the second-to-last letter).
    * **String Reversal:** I managed to easily reverse the entire string using a "magic" method like `[::-1]`.
3.  **String Formatting (Modification):**
    * I used built-in methods like making all letters uppercase (`.upper()`), lowercase (`.lower()`), or only capitalizing the first letter (`.capitalize()`).
4.  **String Verification/Checking:**
    * I checked if a string starts or ends with a specific part using the `startswith()` and `endswith()` methods. This returns a "True" or "False" answer.
5.  **Measurements and Repetition:**
    * I learned how to find the total number of characters in variables (strings) using the `len()` function.
    * I saw how to repeat a string multiple times with a simple operation like `"Mətn" * 10`.

**Müvafiq kod faylı
[03_String_Indeksleme.py](03_String_Indeksleme.py)


### 2. Math Operations and Shortcuts
## Lesson 2: Integers, Calculations, and Comparisons

In this lesson, I learned how to work with basic numbers in Python.

### 1. Numbers and Types

* **int (Integer):** Whole numbers. Example: 5, 8.
* **float (Floating Point Number):** Numbers with a fractional part. Example: 9.5, -2.17.
* **Type Checking:** The command `print(type(number1))` asks Python: "What is the data type of this variable?"

---

### 2. Math Operations and Shortcuts

* **`**`**: Raises to the power (Exponentiation). Example: `5**100`.
* **`//`**: **Floor Division**. It discards the fractional part of the division, returning only the integer part. Example: `14 // 6 = 2`.
* **`*=`**: **Short Assignment**. A shortcut to multiply the variable by a value and assign the result back to the variable (i.e., `l *= 5` means `l = l * 5`).

---

### 3. Built-in Helper Functions

These functions add flexibility to our code:

* **`abs()`**: Returns the **absolute positive value (modulus)** of a number.
* **`round()`**: Rounds fractional numbers. We can also specify the number of decimal places (e.g., `round(number, 3)`).

---

### 4. Type Casting

Converting a value from one type to another:

* **`int()`**: Converts a string (`"100"`) or a float into an **integer**.
* **`str()`**: Converts any number (or other value) into a **string**.

---

### 5. Comparison Operators (Asking Questions)

These operators compare two things and always return **`True`** or **`False`**.

* **`==`**: Is it Equal to?
* **`!=`**: Is it Not Equal to?
* **`< / >`**: Is it Less Than / Greater Than?
* **`<= / >=`**: Is it Less Than or Equal to / Greater Than or Equal to?

**Bu Dərsə Aid Kod:** [İnteger.py](İnteger.py)



