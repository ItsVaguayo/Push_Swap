# push_swap
![42 School](https://img.shields.io/badge/-School-000000?style=flat-square&logo=42&logoColor=white) <br>
A 42 school project focused on sorting a list of integers in **ascending order** using **two stacks**:

- **a** → main stack  
- **b** → auxiliary stack  

You can only use a fixed set of operations, and the objective is to produce the **smallest possible number of moves**.  
The program prints to **stdout** the sequence of operations required to sort stack **a**.

---

## ✨ Features

- **Flexible input**
  - `./push_swap 3 2 1`
  - `./push_swap "3 2 1"`

- **Strong validation**
  - Non-numeric values
  - Duplicates
  - `int` overflow / out-of-range numbers

- **Efficient sorting approaches**
  - Optimized logic for **small stacks (≤ 5)**
  - **Binary LSD radix sort** for bigger inputs (using **indexed values**)

- **42 Norm compliant**

---

## 🧩 Allowed operations

`sa` `sb` `ss` `pa` `pb` `ra` `rb` `rr` `rra` `rrb` `rrr`
![Workflow]([assets/push_swap_visualizer.gif](https://github.com/Edugs94/Push_Swap/raw/main/assets/push_swap_visualizer.gif))

---

## 🛠️ Build

```bash
make        # build push_swap
make clean  # remove object files
make fclean # remove objects + binary
make re     # rebuild everything
```

Flags: `-Wall -Wextra -Werror`

---

## 🚀 Usage

```bash
./push_swap [n1 n2 n3 ...]
./push_swap "n1 n2 n3 ..."
```
---
This project was completed as part of the 42 curriculum.
