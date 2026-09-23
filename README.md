# C programming

> **Coursework** · Foundational exercises
>
> [Selected projects](https://github.com/BadrEss01/BadrEss01#selected-projects) · [Coursework](https://github.com/BadrEss01/BadrEss01/blob/main/COURSEWORK.md)

Foundational C exercises covering expressions, control flow, functions and data structures. Original assignment folders and source comments are preserved.

## Layout

- `a1/`–`a6/`: numbered programming exercises.
- `a7/`: exercises with linked-list and stack helper modules.
- `a8/`: file-processing exercises, queue/stack helpers and text inputs.

## Build one exercise

From the repository root, with GCC installed:

```sh
mkdir -p build
gcc -std=c11 -Wall -Wextra -pedantic a1/a1_3.c -o build/a1_3
./build/a1_3
```

This example was checked during the September 2026 maintenance pass and prints approximately `0.370370`. It is a smoke check, not validation of every exercise.

Build assignments separately: many files define their own `main`. Multi-file exercises need their corresponding helper implementations linked; do not compile every source file into one executable. Preserve the supplied text inputs when running file-based exercises.

## Context

Academic coursework maintained by Badr Essefiany. Generated executables are excluded from the current tree; previous versions remain in Git history.

[Portfolio](https://github.com/BadrEss01/BadrEss01) · [Coursework index](https://github.com/BadrEss01/BadrEss01/blob/main/COURSEWORK.md)
