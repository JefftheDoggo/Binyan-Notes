## Linear transformations and Matrices

- A coordinate can be expressed as a $2 \times 1$ matrix $[{x \atop y}]$
- Transformations to these points can be represented with matrix multiplication, with a $2\times2$ matrix.
	- A $2\times 2$ matrix ($[{a \atop c}{b \atop d}]$) represents 2  transformations
## Reflection

A reflection across an axis can be represented with matrix multiplication:
- $[{-1 \atop 0}{0 \atop 1}][{x \atop y}]$ when you are reflecting across the y-axis
-  $[{1 \atop 0}{0 \atop -1}][{x \atop y}]$ when you are reflecting across the x-axis
- A more general case, reflecting over the line $y = mx$
	- $\theta$ is the angle between $y = mx$ and the positive direction of the x-axis.
	- m = $\tan \theta$ 
	- $y = \tan \theta  \times x$
	- the transformation matrix to reflect over $y = mx$ is $[{\cos 2\theta \atop \sin 2 \theta}{\sin 2 \theta \atop -\cos 2 \theta}]$
## Dilation

- Reflection is like a special case for dilation. 
## Projection

## Translation

## Rotation