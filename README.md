# 🐚 MiniShell – A Basic Linux Shell in C

Welcome to **MiniShell**, a lightweight command-line shell written in C as a part of my journey in mastering Operating Systems and C programming. It is designed to provide a basic Unix-like interface for executing simple commands.

> ⚠️ This is a beginner-level shell and currently supports only basic external commands with no arguments. More advanced features will be added incrementally.

---

## 🚀 Features

- Read and execute external system commands
- Basic shell loop
- Exit command (`exit`) to quit shell
- Forks a child process for each command
- Waits for child process to complete

---

## 🧠 How It Works

1. Prompts user with `minishell>`.
2. Reads input from standard input.
3. Forks a child process using `fork()`.
4. Executes the command using `execvp()`.
5. Waits for the command to finish with `waitpid()`.

---

## 🛠️ How to Build

```bash
gcc main.c -o minishell
```

Make sure you have `gcc` installed. Then run the shell with:

```bash
./minishell
```

---

## 📟 Example Usage

```shell
Welcome to MiniShell! Type 'exit' to quit.
minishell> pwd
/home/yourname/Desktop

minishell> ls
main.c  minishell  README.md

minishell> exit
Goodbye!
```

---

## 📁 Project Structure

```plaintext
📦 MiniShell/
 ┣ 📜 main.c        -> Source code of the shell
 ┣ 📜 README.md     -> Project documentation
```

---

## 👨‍💻 Author

### Nishu Tak

- 🎓 Pre-Final Year BTech CSE with a specilization in ccvt
  
📬 **Connect with me:**

- GitHub: [github.com/Nitanshu715](https://github.com/Nitanshu715)
- LinkedIn: [linkedin.com/in/NitanshuTak](https://www.linkedin.com/in/nitanshu-tak-89a1ba289/?originalSubdomain=in)

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

