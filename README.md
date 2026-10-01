# Robotics-initiative


# Robotics Initiative by Srushti Technologies: Day 02

**Topic:** Basic robot-position calculations (linear algebra)

## 1. Vectors
- A vector has magnitude and direction. Example: v = [3, 4].
- Magnitude: |v| = sqrt(3^2 + 4^2) = 5.
- Types: row, column, zero, unit (magnitude 1).

## 2. Vector addition and robot position
- A = [2, 3], B = [4, 1] -> A + B = [6, 4].
- Robot at P = [5, 3] moves by M = [2, 1] -> P_new = [7, 4].

## 3. Matrices
- Rectangular arrangement of numbers (2x3 = 2 rows, 3 columns).
- Types: square, identity, zero, diagonal.
- Operations: addition/subtraction (same size), scalar multiplication,
  multiplication (m x n)(n x p) = m x p.
- Example: [1 2; 3 4] x [5 6; 7 8] = [19 22; 43 50].
- Multiplication is not commutative: AB != BA.
- Transpose swaps rows and columns: (2x3) becomes (3x2).

## 4. Matrices as transformations
- The columns of a matrix show where the basis vectors land.
- Multiplying matrices composes transformations (applied right to left).

## 5. Determinant
- 2x2: det = ad - bc. Example: [2 3; 1 4] -> 8 - 3 = 5.
- |det| = how much area is scaled.
- det = 0: singular (no inverse), space collapses.
- det != 0: invertible.
- Robotics link: singular configurations.


*Part of the Robotics Initiative by Srushti Technologies, Day 02.*