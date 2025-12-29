# Contributing to python-easter-eggs ✨

First of all, thank you for taking the time to contribute!  
This project celebrates Python’s fun side — Easter eggs, quirks, jokes, and surprising behaviors. Every contribution helps make this collection more delightful and educational.

---

## 📌 What You Can Contribute

You’re welcome to contribute:

- 🥚 **New Python Easter eggs**
- 🤯 **Language quirks or surprising behaviors**
- 📚 **Better explanations or clarifications**
- 🧪 **Minimal runnable examples**
- 📝 **Typos, formatting, or wording improvements**
- 🎨 **Improvements to documentation structure**

---

## 🧠 Contribution Guidelines

To keep the project consistent and high-quality, please follow these rules:

### 1. Keep It Simple
- Examples should be **short and clear**
- Prefer REPL-style snippets (`>>>`) when possible
- Avoid unnecessary complexity

### 2. Follow the Existing Style
Each Easter egg section should include:
- A clear **title**
- A **short explanation**
- A **Python code example**
- An **expected output** (if applicable)

Example structure:

````md
## Easter Egg Title

```python
>>> example()
```

Explanation here.

### Expected output:

```txt
output
```
````

---

## 🧪 Code Rules

- Code examples must work on **CPython**
- Mention version-specific behavior clearly (e.g. *Python 3.9 only*)
- Avoid third-party libraries unless absolutely required
- Do **not** include destructive or unsafe code

---

## 📂 Where to Add Content

- Small additions → directly in `README.md`
- Larger topics → add a new file under `docs/` and link it in the README

---

## 🛠 How to Contribute (Step-by-Step)

1. **Fork** the repository
2. **Create a new branch**

    ```bash
    git checkout -b add-new-easter-egg
    ```
3. Make your changes
4. **Commit** with a clear message

   ```bash
   git commit -m "Add NaN comparison behavior example"
   ```
5. **Push** your branch

   ```bash
   git push origin add-new-easter-egg
   ```
6. Open a **Pull Request**

---

## ✅ Pull Request Checklist

Before submitting, ensure:

* [ ] Code examples are correct
* [ ] Markdown renders properly
* [ ] Output matches the explanation
* [ ] No unrelated changes included
* [ ] Clear description of what you added

---

## 🚫 What Not to Add

Please avoid:

* Opinion-heavy content without technical backing
* Duplicate Easter eggs
* Large binaries or media files
* Breaking existing examples

---

## 🤝 Code of Conduct

By contributing, you agree to follow the project’s
[Code of Conduct](CODE_OF_CONDUCT.md).

Be respectful, kind, and constructive.

---

## 💬 Questions or Ideas?

If you’re unsure whether something fits:

* Open an issue
* Or start a discussion via a pull request
