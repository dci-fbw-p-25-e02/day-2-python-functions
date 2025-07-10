
---

### 1️⃣ **Sum of Squares of Even Numbers**

Write a function `sum_of_squares_of_even_numbers(lst)` that:

* Uses a **lambda** and **filter** to:

  * Find all even numbers in the list.
  * Then square them.
  * Return the sum of these squared even numbers.

#### Example:

```python
sum_of_squares_of_even_numbers([1, 2, 3, 4, 5])  # 20
```

---

### 2️⃣ **Character Count in Words**

Write a function `count_characters_in_words(words)` that:

* Uses a **lambda** and **map** to:

  * Count the number of characters in each word.
  * Return the results as a list.

#### Example:

```python
count_characters_in_words(["apple", "banana", "cherry"])  # [5, 6, 6]
```

---

### 3️⃣ **Filter Odd Numbers**

Write a function `filter_odd_numbers(numbers)` that:

* Uses **filter** and **lambda** to:

  * Filter and return a list of **odd** numbers from a given list.

#### Example:

```python
filter_odd_numbers([1, 2, 3, 4, 5, 6])  # [1, 3, 5]
```

---

### 4️⃣ **Remove Non-Alpha Strings**

Write a function `remove_non_alpha(strings)` that:

* Uses **filter** and **lambda** to:

  * Remove non-alphabetic strings from a list of strings.

#### Example:

```python
remove_non_alpha(["apple", "banana", "123", "kiwi"])  # ["apple", "banana", "kiwi"]
```

---

### 5️⃣ **Sort Students by Age and Grade**

Write a function `sort_students(students)` that:

* Uses **sorted** with a **lambda** function to sort a list of student tuples `('name', age, grade)` by:

  * First by age in **ascending** order.
  * Then by grade in **descending** order.

#### Example:

```python
students = [("Alice", 20, 80), ("Bob", 18, 90), ("Charlie", 20, 70)]
sort_students(students)  
# [('Bob', 18, 90), ('Alice', 20, 80), ('Charlie', 20, 70)]
```

---

### 6️⃣ **Apply Tax to Prices**

Write a function `apply_tax(prices, tax_rate)` that:

* Uses **map** and **lambda** to:

  * Calculate the final price after applying a tax to each price in a list.

#### Example:

```python
apply_tax([100, 200, 300], 0.1)  # [110.0, 220.0, 330.0]
```

---

### 7️⃣ **Find Unique Numbers**

Write a function `find_unique_numbers(numbers)` that:

* Uses **set** and **lambda** to:

  * Find the **unique numbers** from a list (removes duplicates).

#### Example:

```python
find_unique_numbers([1, 2, 2, 3, 4, 4, 5])  # [1, 2, 3, 4, 5]
```

---

### 8️⃣ **Product of Numbers in a List**

Write a function `product_of_numbers(numbers)` that:

* Uses **reduce** and **lambda** to:

  * Multiply all numbers in the list together.

#### Example:

```python
product_of_numbers([1, 2, 3, 4])  # 24
```

---

### 9️⃣ **Filter and Transform Data**

Write a function `filter_and_transform(data)` that:

* Uses **filter** to keep even numbers.
* Then, use **map** to double those even numbers.

#### Example:

```python
filter_and_transform([1, 2, 3, 4, 5, 6])  # [4, 8, 12]
```

---

### 🔟 **Filter Names Starting with 'A' or 'B'**

Write a function `filter_names(names)` that:

* Uses **filter** and **lambda** to:

  * Filter names that start with **'A'** or **'B'**.

#### Example:

```python
filter_names(["Alice", "Bob", "Charlie", "David"])  # ["Alice", "Bob"]
```

---

### 1️⃣1️⃣ **Zip Names and Prices**

Write a function `zip_names_and_prices(names, prices)` that:

* Uses **zip** to combine two lists of names and prices into a list of tuples.

#### Example:

```python
zip_names_and_prices(["apple", "banana", "cherry"], [1.5, 2.5, 3.5])  
# [("apple", 1.5), ("banana", 2.5), ("cherry", 3.5)]
```

---

### 1️⃣2️⃣ **Find Longest Word in List**

Write a function `longest_word(words)` that:

* Uses **reduce** and **lambda** to:

  * Find the **longest word** in a list of strings.

#### Example:

```python
longest_word(["apple", "banana", "kiwi", "cherry"])  # "banana"
```

---

### 🔥 **Bonus 1: Capitalize First and Last Letters**

Write a function `capitalize_first_and_last(word)` that:

* Uses **lambda** to capitalize the **first** and **last** letter of a string.
* Return the modified string.

#### Example:

```python
capitalize_first_and_last("hello")  # "HellO"
```

---

### 🔥 **Bonus 2: Calculate the Average of Numbers**

Write a function `average(numbers)` that:

* Uses **lambda**, **map**, and **reduce** to calculate the **average** of numbers in a list.

#### Example:

```python
average([1, 2, 3, 4, 5])  # 3.0
```

---

