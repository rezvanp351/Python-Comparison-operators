# Python-Comparison-operators
Comparison operators are used to compare two values:

Comparison operators are used to compare two values.  
They always return a **Boolean result**: either `True` or `False`.

---

## 📊 Comparison Operators Table

| Operator | Symbol | Example | Result |
|----------|--------|---------|--------|
| Equal | `==` | `5 == 5` | `True` |
| Not Equal | `!=` | `5 != 3` | `True` |
| Greater Than | `>` | `7 > 3` | `True` |
| Less Than | `<` | `2 < 5` | `True` |
| Greater Than or Equal | `>=` | `5 >= 5` | `True` |
| Less Than or Equal | `<=` | `3 <= 7` | `True` |

---

## 📝 Explanation of Each Operator

### 1. Equal (`==`)
Checks if two values are equal.  
```python
x = 10
y = 10
print(x == y)   # True
```

---

### 2. Not Equal (`!=`)
Checks if two values are **not** equal.  
```python
x = 8
y = 5
print(x != y)   # True
```

---

### 3. Greater Than (`>`)
Checks if the left value is greater than the right value.  
```python
print(15 > 7)   # True
```

---

### 4. Less Than (`<`)
Checks if the left value is smaller than the right value.  
```python
print(4 < 9)    # True
```

---

### 5. Greater Than or Equal (`>=`)
Checks if the left value is greater or equal to the right value.  
```python
print(12 >= 12) # True
```

---

### 6. Less Than or Equal (`<=`)
Checks if the left value is smaller or equal to the right value.  
```python
print(6 <= 10)  # True
```

---

## 🎉 Fun Examples

```python
# Compare strings
print("apple" == "apple")   # True
print("apple" < "banana")   # True (because 'a' comes before 'b')

# Compare booleans
print(True == 1)   # True (Python treats True as 1)
print(False == 0)  # True (Python treats False as 0)

# Compare lists
print([1,2,3] == [1,2,3])  # True
print([1,2,3] != [3,2,1])  # True
```

---

## ✅ Conclusion

- Comparison operators are used to **compare values**.  
- They always return `True` or `False`.  
- They work not only with **numbers**, but also with **strings, booleans, and collections**.  
- They are often combined with **logical operators** (`and`, `or`, `not`) to create more complex conditions.

---
