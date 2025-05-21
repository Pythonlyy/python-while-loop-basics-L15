# 🔁 Repeat Until False: Using `while` Loops in Python

A `while` loop keeps going **as long as a condition is true**. It's perfect when you don't know how many times you'll need to repeat something.

---

## 💡 What You'll Learn

* How `while` loops work
* When to use them instead of `for` loops
* How to avoid infinite loops

---

## 🧠 When to Use

* Use `while` when **you don't know** how many repetitions you need
* Use `for` when you’re counting or looping through a fixed list

---

## 💻 Example with Explanation

```python
x = 0

while x < 3:
    print(x)
    x += 1
```

### 🔈 Output

```
0
1
2
```

✅ The loop runs **while `x < 3` is true**.

Each time through the loop, we print `x` and then increase it by 1.

---

## 🧨 Be Careful! Infinite Loop Warning

```python
# This will never stop!
while True:
    print("Oops")
```

Always change something inside the loop so it eventually stops.

---

## 📌 Pro Tips

* Update the loop variable inside the loop (`x += 1`)
* Use `break` to exit early if needed
* Use `while` for input validation or waiting for a condition to change

---

## 🧪 Try It Yourself

```python
countdown = 5

while countdown > 0:
    print(countdown)
    countdown -= 1

print("Liftoff!")
```

### 🔈 Expected Output

```
5
4
3
2
1
Liftoff!
```

---

❓ **When would you use a `while` loop instead of a `for` loop?**
Let me know below 👇

---

🐍 This is part of the **Pythonly** beginner series.
Learn Python one line at a time. Follow **@Pythonly** for more.

---


