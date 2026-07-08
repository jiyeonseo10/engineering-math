# Theory

## Separable Differential Equations

A separable differential equation is a first-order differential equation that can be written in the form

\[
\frac{dy}{dx}=f(x)g(y)
\]

The variables can be separated as

\[
\frac{1}{g(y)}\,dy=f(x)\,dx
\]

After separating the variables, integrate both sides.

\[
\int \frac{1}{g(y)}\,dy
=
\int f(x)\,dx
\]

Finally, apply the initial condition (if given) to determine the constant of integration.

---

## General Solution

The result after integration is called the **general solution**.

It contains an arbitrary constant \(C\).

Example

\[
y=C e^{2x}
\]

---

## Particular Solution

When an initial condition is provided, substitute it into the general solution to determine \(C\).

Example

\[
y(0)=2
\]

\[
2=C
\]

Therefore,

\[
y=2e^{2x}
\]

---

## Solution Procedure

1. Write the differential equation.
2. Separate the variables.
3. Integrate both sides.
4. Solve for the constant using the initial condition.
5. Write the final solution.

---

## Mathematical Modeling

Many real-world phenomena can be represented by differential equations.

Examples include

- Population growth
- Radioactive decay
- Cooling and heating
- Motion
- Mixing problems

---

## Key Formulas

Variable Separation

\[
\frac{dy}{dx}=f(x)g(y)
\]

↓

\[
\frac{1}{g(y)}dy=f(x)dx
\]

↓

Integrate both sides.

---

## Notes

- Always separate the variables before integrating.
- Do not forget the constant of integration.
- Use the initial condition only after obtaining the general solution.
- Check whether the variables can actually be separated before applying this method.
