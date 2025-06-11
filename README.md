# Mini-Project-02  
## Challenge Question 1 – Sorting a Heterogeneous List in Python

---

### 📄 Problem Statement

Write a Python program to sort a list containing **heterogeneous data** (i.e., both strings and integers).

#### 🔸 Given Example:
```python
L = ["Ram", 1, "Shyam", 2, "Aman", 3]
print(L)
L.sort()
print(L)

----

🧠 Methodology
- Separate the list based on data types .  
- Create two new lists:  
  - One containing all the strings  
  - One containing all the integers  
- Sort both lists individually using `sort()` or `sorted()`.  
- Combine the sorted lists if a unified result is needed.  
- This avoids `TypeError` caused by comparing strings and integers during sorting.
