# replace-letter-cpp

# C++ String Programs

A collection of beginner-friendly C++ programs that work with strings. Made while learning C++ in B.Tech CSE, 1st semester.

## Programs

| # | Program | File | Description |
|---|---------|------|-------------|
| 1 | Reverse a String | `reverse_string.cpp` | Prints the entered string in reverse order |
| 2 | Replace Each Letter with Next Alphabet | `next_alphabet.cpp` | Replaces every letter with the next one (`a` -> `b`, `z` -> `a`) |

---

## 1. Reverse a String

Takes a string as input (spaces included) and prints it in reverse order using a `for` loop that starts from the last character.

**Example:**

```
Enter a string: Hello World
Reversed string: dlroW olleH
```

**Logic:**
1. Read the full line using `getline(cin, str)`.
2. Start a loop at the last index (`str.length() - 1`) and go down to `0`.
3. Add each character to a new string `rev`.
4. Print `rev`.

---

## 2. Replace Each Letter with Next Alphabet

Replaces each letter with the next letter of the alphabet. `z` becomes `a` and `Z` becomes `A`. Spaces, digits and symbols stay unchanged.

**Example:**

```
Enter a string: Hello Zebra 123
Result: Ifmmp Afcsb 123
```

**Logic:**
1. Read the full line using `getline(cin, str)`.
2. Go through each character one by one.
3. If it is `z` or `Z`, wrap around to `a` or `A`.
4. If it is any other letter, add 1 to its ASCII value to get the next letter.
5. Leave all other characters as they are.

---

## Concepts Used

- Strings (`string`)
- Input and output (`cin`, `cout`, `getline`)
- `for` loop
- `if` / `else if` conditions
- String indexing (`str[i]`)
- ASCII values of characters

## How to Run

Make sure a C++ compiler such as `g++` is installed.

```bash
# Compile
g++ reverse_string.cpp -o reverse_string
g++ next_alphabet.cpp -o next_alphabet

# Run (Linux / macOS)
./reverse_string
./next_alphabet

# Run (Windows)
reverse_string.exe
next_alphabet.exe
```

## Project Structure

```
cpp-string-programs/
├── README.md
├── reverse_string.cpp
└── next_alphabet.cpp
```

## Author

NAYLA IRFAN 
B.Tech CSE

## License

This project is free to use for learning purposes.
