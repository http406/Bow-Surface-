# Bow-Surface-

The mathematical equation that is being used in the code can be written as:

\[
\mathbf{r}(u, v) = 
\begin{bmatrix}
x(u, v) \\
y(u, v) \\
z(u, v)
\end{bmatrix}
\]

Where:

\[
x(u, v) = 2 + T \cdot \sin(2 \pi u) \cdot \sin(4 \pi v)
\]
\[
y(u, v) = 2 + T \cdot \sin(2 \pi u) \cdot \cos(4 \pi v)
\]
\[
z(u, v) = T \cdot \cos(2 \pi u) + 3 \cdot \cos(2 \pi v)
\]

### Explanation of the terms:

- **\(u\)** and **\(v\)** are parameters, where each ranges from 0 to 1, and they control the surface's shape. These parameters are then scaled to the range of -1 to 1 in the code (`u = u * 2 - 1` and `v = v * 2 - 1`).
- **\(T\)** is a constant, which is set to 1 in the code. This constant scales the amplitude of the sine and cosine terms and influences the overall "size" of the wave-like oscillations.
- **π** is a mathematical constant (approximately 3.14159), used to create periodic oscillations in the sine and cosine functions.

### How the surface looks:
- The **\(x\)** and **\(y\)** components are influenced by both sine and cosine functions of the parameters \(u\) and \(v\). The sine and cosine terms create oscillatory patterns in the \(x\) and \(y\) directions, which results in the surface having wave-like behavior in the horizontal plane.
- The **\(z\)** component introduces depth and adds another layer of oscillation in the vertical direction, combining two cosine functions of \(u\) and \(v\) to form a complex wave-like shape.

Together, this equation defines a complex, oscillating 3D surface that has curving, wave-like patterns in all directions, making it look like a "bow" shape in 3D space.
