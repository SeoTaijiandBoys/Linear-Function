
## Linear System Solver

### Overview

This Python script solves a system of linear equations of the form:

```
A1*X1 + B1*X2 + C1*X3 + ... = P1
A2*X1 + B2*X2 + C2*X3 + ... = P2
...
An*X1 + Bn*X2 + Cn*X3 + ... = Pn
```

The program uses NumPy to compute the solution vector (X) for the system.

### How to Use

1. **Clone the Repository:**
   ```
   git clone https://github.com/your-username/linear-system-solver.git
   cd linear-system-solver
   ```

2. **Run the Script:**
   ```
   python linear_system_solver.py
   ```

3. **Follow the Prompts:**
   - Enter the number of equations in the system (n).
   - Input the coefficients for each equation as prompted.

4. **View the Solution:**
   - The program will display the solution vector (X) with the values for each unknown.

### Example

Suppose you have a system of two equations:

```
2*X1 + 3*X2 = 8
4*X1 - 2*X2 = 6
```

You would run the script, enter 2 as the number of equations, and input the coefficients as instructed. The script will then provide the solution for X1 and X2.

### Notes

- Ensure that the system is properly defined with the correct number of equations and coefficients.
- Press ENTER after entering each coefficient.
