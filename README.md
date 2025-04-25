# 📚 Quote Collector

A beginner-friendly project to practice Git version control commands like `add`, `commit`, and `push` using a simple text-based quote collection. Ideal for those new to Git and looking for hands-on experience.

---

## 🚀 Features

- Add your favorite quotes.
- Track file changes using Git.
- Practice core Git concepts: working directory, staging area, and commits.
- Easily extendable for learning Git branching, merging, and collaboration.

---

## 📁 Project Structure

```
quote-collector/
├── quotes.txt   # Contains your favorite quotes.
└── README.md    # Project information and setup.
```

---

## 🛠️ How to Use

1. **Clone or Create the Project Folder:**

   ```bash
   mkdir quote-collector
   cd quote-collector
   ```

2. **Create the File:**

   ```bash
   echo "Be yourself; everyone else is already taken. – Oscar Wilde" > quotes.txt
   ```

3. **Initialize a Git Repository:**

   ```bash
   git init
   ```

4. **Stage the File:**

   ```bash
   git add quotes.txt
   ```

5. **Commit the Changes:**

   ```bash
   git commit -m "Initial commit: Added a famous quote to quotes.txt"
   ```

6. **🔗 Optional: Push to GitHub**

   - Create a GitHub repo named `quote-collector`, then:

     ```bash
     git remote add origin https://github.com/yourusername/quote-collector.git
     git branch -M main
     git push -u origin main
     ```

---

## 💡 Next Steps

- Add more quotes and commit changes:

   ```bash
   echo "Your next quote here." >> quotes.txt
   git add quotes.txt
   git commit -m "Added another quote"
   ```

- Practice checking status and diffs:

   ```bash
   git status
   git diff
   ```

- Explore resetting and reverting changes.

---

## 🙌 Contributing

This is a practice project, but feel free to fork, expand it, or use it for Git tutorials.

---

## 📜 License

This project is licensed under the MIT License.
```
