# Exercise 1. Matrix Size and Entries — Solution to github

## 1. Problem Statement

Given the matrices

$$
A=
\begin{pmatrix}
2 & -1 & 3 \\
0 & 4 & 5 \\
\end{pmatrix},
\qquad
B=
\begin{pmatrix}
1 & 0 \\
-2 & 3 \\
4 & 1 \\
\end{pmatrix}
$$

**Tasks:**

1. State the sizes of matrices $A$ and $B$.
2. Read off the entries $a_{12}$, $a_{23}$, $b_{21}$, and $b_{32}$.
3. Write the second row of $A$ and the first column of $B$ as vectors.

**Why this exercise:** Builds basic fluency with matrix notation, indices, rows, and columns.

---

## 2. Essential Theory and Formulas

### 2.1. What is a matrix?

A **matrix** is a rectangular arrangement of numbers organized into rows and columns.

For example,

$$
M=
\begin{pmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
\end{pmatrix}
$$

This matrix has:

- **2 rows** (horizontal lines of numbers).
- **3 columns** (vertical lines of numbers).

The size of a matrix is written as

$$
m \times n
$$

where:

- $m$ is the number of rows,
- $n$ is the number of columns.

Therefore, the example matrix $M$ has size $2 \times 3$.

**Important:** The number of rows always comes first.

### 2.2. Matrix entries and indices

Each number inside a matrix is called an **entry** or **element**.

We use two indices to identify its position:

$$
a_{ij}
$$

where:

- $i$ indicates the row number,
- $j$ indicates the column number.

For example, consider

$$
C=
\begin{pmatrix}
7 & 8 & 9 \\
2 & 4 & 6 \\
\end{pmatrix}
$$

To find $c_{23}$:

1. The first index is $2$, so choose row 2.
2. The second index is $3$, so choose column 3.
3. The number at their intersection is $6$.

Therefore,

$$
c_{23}=6
$$

Similarly,

$$
c_{12}=8
$$

because $8$ is in row 1, column 2.

**Remember:** First index = row, second index = column.

### 2.3. Row vectors and column vectors

A **row vector** is a matrix containing only one row.

Example:

$$
\begin{pmatrix}
2 & 5 & 7 \\
\end{pmatrix}
$$

Its size is $1 \times 3$.

A **column vector** is a matrix containing only one column.

Example:

$$
\begin{pmatrix}
2 \\
5 \\
7 \\
\end{pmatrix}
$$

Its size is $3 \times 1$.

The distinction is important: the numbers may be identical, but their arrangement is different.

---

## 3. Step-by-Step Solution

### Task 1. Determine the sizes of $A$ and $B$

**Matrix A**

$$
A=
\begin{pmatrix}
2 & -1 & 3 \\
0 & 4 & 5 \\
\end{pmatrix}
$$

Step 1: Count the rows.

There are 2 rows:

- Row 1: $(2,-1,3)$
- Row 2: $(0,4,5)$

Step 2: Count the columns.

There are 3 columns.

Step 3: Write the size.

$$
\mathrm{size}(A)=2\times 3
$$

**Matrix B**

$$
B=
\begin{pmatrix}
1 & 0 \\
-2 & 3 \\
4 & 1 \\
\end{pmatrix}
$$

Step 1: Count the rows.

There are 3 rows.

Step 2: Count the columns.

There are 2 columns.

Step 3: Write the size.

$$
\mathrm{size}(B)=3\times 2
$$

**Answer to Task 1:**

$$
A: 2\times 3,
\qquad
B: 3\times 2
$$

### Task 2. Find the specified matrix entries

Recall that $a_{ij}$ represents the entry in row $i$ and column $j$.

**Entry $a_{12}$**

- First index: 1 (row 1).
- Second index: 2 (column 2).
- The number at this position is $-1$.

$$
a_{12}=-1
$$

**Entry $a_{23}$**

- First index: 2 (row 2).
- Second index: 3 (column 3).
- The number at this position is $5$.

$$
a_{23}=5
$$

**Entry $b_{21}$**

- First index: 2 (row 2).
- Second index: 1 (column 1).
- The number at this position is $-2$.

$$
b_{21}=-2
$$

**Entry $b_{32}$**

- First index: 3 (row 3).
- Second index: 2 (column 2).
- The number at this position is $1$.

$$
b_{32}=1
$$

**Answer to Task 2:**

$$
a_{12}=-1,\qquad a_{23}=5
$$

$$
b_{21}=-2,\qquad b_{32}=1
$$

### Task 3. Write the requested vectors

**Second row of matrix A**

We have

$$
A=
\begin{pmatrix}
2 & -1 & 3 \\
0 & 4 & 5 \\
\end{pmatrix}
$$

Step 1: Identify the second row.

The numbers are $0$, $4$, and $5$.

Step 2: Write them horizontally as a row vector.

$$
\mathbf{r}_2=
\begin{pmatrix}
0 & 4 & 5 \\
\end{pmatrix}
$$

This is a $1\times 3$ row vector.

**First column of matrix B**

We have

$$
B=
\begin{pmatrix}
1 & 0 \\
-2 & 3 \\
4 & 1 \\
\end{pmatrix}
$$

Step 1: Identify the first column.

Reading from top to bottom gives $1$, $-2$, and $4$.

Step 2: Write these numbers vertically as a column vector.

$$
\mathbf{c}_1=
\begin{pmatrix}
1 \\
-2 \\
4 \\
\end{pmatrix}
$$

This is a $3\times 1$ column vector.

---

## 4. Verification

We can verify all results by checking the original matrices.

**Matrix sizes:**

- Matrix $A$ contains 2 rows, each with 3 entries.
- Matrix $B$ contains 3 rows, each with 2 entries.

**Matrix entries:**

| Entry | Row | Column | Value |
|---|---|---|---|
| $a_{12}$ | 1 | 2 | $-1$ |
| $a_{23}$ | 2 | 3 | $5$ |
| $b_{21}$ | 2 | 1 | $-2$ |
| $b_{32}$ | 3 | 2 | $1$ |

All entries agree with the original matrices.

**Vectors:**

- The second row of $A$ is $(0,4,5)$.
- The first column of $B$ contains $1$, $-2$, and $4$, in that order.

Therefore, all results are correct.

---

## 5. Final Answers

**1. Matrix sizes**

$$
A: 2\times 3,
\qquad
B: 3\times 2
$$

**2. Matrix entries**

$$
a_{12}=-1,\quad a_{23}=5,\quad
b_{21}=-2,\quad b_{32}=1
$$

**3. Row and column vectors**

Second row of $A$:

$$
\begin{pmatrix}
0 & 4 & 5 \\
\end{pmatrix}
$$

First column of $B$:

$$
\begin{pmatrix}
1 \\
-2 \\
4 \\
\end{pmatrix}
$$

---

## 6. Key Points to Remember

1. A matrix of size $m\times n$ has $m$ rows and $n$ columns.
2. In $a_{ij}$, the first index identifies the row and the second identifies the column.
3. A row vector is written horizontally and has size $1\times n$.
4. A column vector is written vertically and has size $m\times 1$.
5. Matrix indexing starts at 1 in standard mathematical notation, not at 0.
