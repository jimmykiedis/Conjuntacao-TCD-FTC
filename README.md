# 🧮 Conjuntão C™

<p align="center">
  <em>Academic project for the Fundamentals of Computer Technology (FTC) course — UFGD 🎓</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white" alt="C">
  <img src="https://img.shields.io/badge/GCC-compiler-A42E2B?style=flat&logo=gnu&logoColor=white" alt="GCC">
  <img src="https://img.shields.io/badge/status-completed-brightgreen" alt="Status: completed">
  <img src="https://img.shields.io/badge/platform-Windows%20%7C%20Linux-lightgrey" alt="Platforms: Windows and Linux">
  <img src="https://img.shields.io/badge/license-MIT-blue" alt="MIT License">
</p>

---

**Conjuntão C™** is a terminal program written in C to perform set operations and check properties of mathematical relations. It was created as an academic exercise for the Fundamentals of Computer Technology (FTC) course at UFGD.

The program presents an interactive menu with two main areas: classic operations between sets and analysis of relational properties.

## 🎯 Repository Objective

Bring together a didactic implementation of the fundamental concepts of programming logic in C, applying arrays, loop structures, functions, flow control, and mathematical reasoning about sets and relations.

## ✨ Topics Covered

- Union, intersection, and difference operations between sets.
- Verification of the reflexive, symmetric, and transitive properties of relations.
- Use of arrays, `for` and `while` loops, `switch` structures, and functions.
- Basic input and buffer control with `getchar()`.
- Use of `stdbool.h` for logical tests.
- Terminal clearing adapted for Windows and Linux.

## 🛠 How to Download the Repository

📥 1. Clone the repository with Git:

```bash
git clone Conjuntacao-TCD-FTC.git
cd conjuntao-c
```

If you don't use Git, download the project as a ZIP file from the repository page and extract it into a local folder.

🔗 2. Compile

You need to have the GCC compiler installed.

To generate the object file:

```bash
gcc -Wall -Wextra -c FTC.c -o FTC.o
```

To generate the executable from the object file:

```bash
gcc FTC.o -o output/FTC.exe
```

Or compile directly with a single command:

```bash
gcc -Wall -Wextra FTC.c -o output/FTC.exe
```

▶️ 3. Run

On Windows:

```bash
./output/FTC.exe
```

On Linux, generate an executable without the `.exe` extension and run it with:

```bash
./output/FTC
```

Follow the options shown in the menu to enter the sets or relations you want to analyze.

## 🏗️ Implementation Strategy

The program represents sets and relations using arrays with a maximum capacity defined by the `MAX` constant. Set operations iterate through the elements to identify results and avoid duplicates. Relational properties, in turn, are verified by comparing the given pairs, following the mathematical definitions of reflexivity, symmetry, and transitivity.

## 🛠️ Technologies

| Technology | Use in the project |
| --- | --- |
| C (C99 or higher) | Main language of the program |
| GCC | Compilation of the source code |
| `stdbool.h` | Boolean values in the property tests |
| C standard libraries | Input, output, and other program resources |

No external library is required.

## 📁 Project Structure

```text
conjuntao-c/
├── FTC.c          # Main source code
├── FTC.o          # Object file generated during compilation
├── output/        # Generated executable
└── README.md      # Project documentation
```

## 📝 Final Notes

- The limit of elements per set is **20**, defined by `#define MAX 20`.
- Set operations avoid duplicate elements in the result.
- Input handling was designed for didactic purposes and does not have robust validation; follow the instructions shown in the terminal.
- The project is complete and serves as study material and an initial reference for programming in C.

## 📄 License

This is an academic project developed for study purposes in the Fundamentals of Computer Technology (FTC) course — UFGD, in 2025.

The content may be consulted, studied, and adapted for educational purposes. To formally adopt the MIT license indicated in the badge, include a `LICENSE` file with the full text of the license.

---

<p align="center">🎯 Academic project — UFGD — 2025</p>
