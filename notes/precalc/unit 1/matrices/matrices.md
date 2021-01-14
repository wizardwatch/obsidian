dimensions are in x,y format. 
## adding and subtracting matrices
- you can only add and subtract matrices with the same dimensions. 

## multiplying matrices
- the y dimension of the matrices must match the x dimensions in the second. 
	- if we take the dimensions (x$_1$, y$_1$) and (x$_2$, y$_2$) Than y$_1$ must equal x$_2$.
- the out side numbers, the first factor of the first matrix and the second number of the second matrix, represent the end dimensions. 
	-  if we take the dimensions (x$_1$, y$_1$) * (x$_2$, y$_2$)  than the resulting dimensions are (x$_1$, y$_2$)
- multiplication example
	- $\begin{bmatrix}1&2&3\\4&5&6\end{bmatrix}$  * $\begin{bmatrix}7&8\\9&10\\11&12\end{bmatrix}$ =  $\begin{bmatrix}58&10\\11&12\end{bmatrix}$
	- example explained. For each place, moving left to right from the top by row, multiply the current row times the current column. For the first part of the example problem we multiply 1 * 7, 2 * 9, and 3 * 11. We add the numbers and find that 7 + 18 + 33 is 58.