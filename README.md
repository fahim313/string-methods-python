# 🐍 Python String Methods Cheat Sheet with Examples

A beginner-friendly reference for Python string methods with explanations and practical examples.

---

## 🔹 Basic Info

| Method | What It Does | Why Use It | Example |
|--------|---------------|-------------|---------|
| `len(s)` | Returns length of string | To count characters | `len("apple") → 5` |
| `type(s)` | Returns the data type | To confirm it’s a string | `type("apple") → <class 'str'>` |

---

## 🔹 Case Conversion

| Method | What It Does | Why Use It | Example |
|--------|---------------|-------------|---------|
| `s.lower()` | Converts to lowercase | For case-insensitive comparison | `"Hello".lower() → "hello"` |
| `s.upper()` | Converts to uppercase | For uniform formatting | `"hello".upper() → "HELLO"` |
| `s.title()` | Capitalizes each word | For title case formatting | `"my name is fahim".title() → "My Name Is Fahim"` |
| `s.capitalize()` | Capitalizes only first letter | For sentence formatting | `"python is fun".capitalize() → "Python is fun"` |
| `s.swapcase()` | Swaps cases | Formatting changes | `"PyThOn".swapcase() → "pYtHoN"` |

---

## 🔹 Searching & Finding

| Method | What It Does | Why Use It | Example |
|--------|---------------|-------------|---------|
| `s.find('x')` | Returns first index | To locate substring | `"apple".find("p") → 1` |
| `s.rfind('x')` | Returns last index | To find from right | `"apple pie".rfind("p") → 6` |
| `s.index('x')` | Like `find()`, but raises error | For strict match | `"apple".index("l") → 3` |
| `s.count('x')` | Counts occurrences | For frequency check | `"banana".count("a") → 3` |

---

## 🔹 Validation Methods

| Method | What It Does | Why Use It | Example |
|--------|---------------|-------------|---------|
| `s.isalpha()` | Checks only letters | Input validation | `"hello".isalpha() → True` |
| `s.isdigit()` | Checks only digits | For numeric inputs | `"123".isdigit() → True` |
| `s.isalnum()` | Letters + digits | For usernames | `"abc123".isalnum() → True` |
| `s.isspace()` | Checks if only whitespace | Blank input check | `"   ".isspace() → True` |
| `s.islower()` | All lowercase? | Case checking | `"python".islower() → True` |
| `s.isupper()` | All uppercase? | Case checking | `"HELLO".isupper() → True` |
| `s.istitle()` | Title format? | For validation | `"Python Is Fun".istitle() → True` |

---

## 🔹 Modification & Replacement

| Method | What It Does | Why Use It | Example |
|--------|---------------|-------------|---------|
| `s.strip()` | Removes space from both ends | Clean input | `"  hello  ".strip() → "hello"` |
| `s.lstrip()` | Removes leading space | Clean start | `"  hello".lstrip() → "hello"` |
| `s.rstrip()` | Removes trailing space | Clean end | `"hello  ".rstrip() → "hello"` |
| `s.replace('a','b')` | Replaces text | To change parts of string | `"banana".replace("a", "o") → "bonono"` |
| `s.translate()` | Advanced character replacement | Complex transforms | ❗ Requires mapping, skip for now |

---

## 🔹 Splitting & Joining

| Method | What It Does | Why Use It | Example |
|--------|---------------|-------------|---------|
| `s.split()` | Splits by space | To convert to list | `"a b c".split() → ["a", "b", "c"]` |
| `s.split(',')` | Splits by comma | For CSV handling | `"a,b,c".split(',') → ["a", "b", "c"]` |
| `s.rsplit()` | Splits from right | To limit split from end | `"a b c".rsplit(maxsplit=1) → ["a b", "c"]` |
| `' '.join(list)` | Joins list to string | To combine strings | `' '.join(["a", "b", "c"]) → "a b c"` |

---

## 🔹 Start & End Checking

| Method | What It Does | Why Use It | Example |
|--------|---------------|-------------|---------|
| `s.startswith('x')` | Checks prefix | To verify beginning | `"python".startswith("py") → True` |
| `s.endswith('x')` | Checks suffix | To verify ending | `"main.py".endswith(".py") → True` |

---

## 🔹 Alignment & Padding

| Method | What It Does | Why Use It | Example |
|--------|---------------|-------------|---------|
| `s.center(width)` | Centers text | For alignment | `"hi".center(10) → "    hi    "` |
| `s.ljust(width)` | Left-aligns text | Add right padding | `"hi".ljust(10) → "hi        "` |
| `s.rjust(width)` | Right-aligns text | Add left padding | `"hi".rjust(10) → "        hi"` |
| `s.zfill(width)` | Pads with 0 | For fixed-width numbers | `"42".zfill(5) → "00042"` |

---

## 🔹 Encoding

| Method | What It Does | Why Use It | Example |
|--------|---------------|-------------|---------|
| `s.encode()` | Converts to bytes | For file/network processing | `"hello".encode() → b'hello'` |

---

## 🔹 Other Useful

| Method | What It Does | Why Use It | Example |
|--------|---------------|-------------|---------|
| `eval(s)` | Evaluates expression | To compute from string | `eval("2 + 3 * 5") → 17` |
| `format()` | Formats strings | For dynamic output | `"Hi {}, score: {}".format("Fahim", 95) → "Hi Fahim, score: 95"` |

---

## 📌 Author

**Fahim Sahriiar**  
🎯 Python Explorer  
🌐 [GitHub Profile](https://github.com/fahim313)

---

## 📚 License

This project is licensed under the **MIT License** — feel free to use, modify, and share!



