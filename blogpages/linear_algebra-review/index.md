## An Engineer's Review of Linear Algebra (*under construction*)
A good understanding of linear algebra is a must for computer scientists who like to delve deeper into the world of machine learning, especially deep learning. I try to provide explanations to some of the practical aspects of Linear Algebra in the context of computer science.

### A brief travel in time:

  Around the turn of 200 B.C, the Chinese published the ["The Nine Chapters on the Mathematical Art"]("https://en.wikipedia.org/wiki/The_Nine_Chapters_on_the_Mathematical_Art") in which they introduces a way of solving 3x3 equations which is now called the referred to as Gaussian Elimination<sup>[1]</sup>. However, it was not until the 17th century the power of Linear Algebra was known.\
  René Descartes introduced what is now popularly referred to as the ["Cartesian Geometry"](https://en.wikipedia.org/wiki/Cartesian_geometry). In this new system, lines and planes are represented by system of linear equations and the intersection of these lines are the solutions to the system of linear equations. Leibniz introduced a systematic way of solving these system of linear equation using Determinants(link to later part in the page) in the late 17th century[1]. \
  In the mid 19th century, Arthur Caley introduced matrix multiplication and matrix inverses and tied matrices with determinants.Cayley used a single letter to denote a matrix, thus treating a matrix as an aggregate object. He also realized the connection between matrices and determinants, and wrote "There would be many things to say about this theory of matrices which should, it seems to me, precede the theory of determinants"[1].\
  Linear algebra took its modern form in the first half of the 20th century. The advent of computers in the later half of the 20th century elicited many computer scientists to develop new algorithms for efficient computation of matrix decompositions and solutions to system of linear equations. 
  
### Some definition of the words used widely:

- **Scalar**: A scalar is nothing but a single number. Notation: Lower case letter
- **Vector**: A vector is an array of numbers. For ease of notation, a vector is represented by lower case bold letters throughout this page. **x** is a column vector with *n* scalar values.  

  Example:  \
    **x** is a vector in **R**<sup>3</sup>. \
    **x<sub>1</sub>** = 
  <img src="https://render.githubusercontent.com/render/math?math=\begin{pmatrix}
  x_{11} \\
  x_{12}\\
  x_{13}\\
  \end{pmatrix}">
- **Matrix**: A matrix is nothing more than a 2D array of numbers. Columns of a matrix are individual vectors. Notation: Matrices are represented in upper case bold letters.

  Example:  \
    **A** is a matrix of size 3x3 composed of 3 vectors of size 3x1.  \
    **A** = $$\begin{pmatrix}  | & | & |\\
          x_{1}&x_{2}&x_{3}\\
          | & | & | \\ \end{pmatrix}$$

<!--   <img src="https://render.githubusercontent.com/render/math?math=\begin{pmatrix}
          x_{11}&x_{21}&x_{31}\\
          x_{12}&x_{22}&x_{32}\\
          x_{13}&x_{23}&x_{33}\\
          \end{pmatrix}"> -->

  
  

### ____________________________________________________
- Vectors and vectors spaces
- Dot product of vectors
- Determinant and inverses
- Eigen Values and Eigen Decomposition
- SVD
- Intro to matrix calculus
