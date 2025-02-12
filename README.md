## Personal Information
*Name:* Md Hasibul Hossain Rafin  
*ID:* 2215151031  
*University:* UITS (University of Information Technology and Sciences)  
*Department:* Computer Science and Engineering (CSE)  
*Batch:* 51  
*Section:* 7A2  

## Course Details
*Course Code:* CSE 413  
*Course Name:* Simulation and Modeling Lab  
*Course Teacher:* Audity Ghosh

## Tasks
1. Generate two vectors with 15 random floats, plot them, and label axes.
2. Create a 4x4 random matrix, visualize as a heatmap, and label rows/columns.
3. Generate two 4x4 matrices, perform arithmetic operations, and visualize with bar plots.

## Explanation 
*For qus 1:* 
 
- **`np.random.rand(15)`** → Generates **15 random floating-point numbers** between **0 and 1** for each vector (`V1` and `V2`).  
- **`np.arange(len(V1))`** → Creates an index array `[0, 1, 2, ..., 14]`, which serves as the x-axis values.  
- **`plt.plot()`** → Plots the vectors with different **markers** and **line styles** for better visualization.  
- **`plt.xlabel()`, `plt.ylabel()`, `plt.title()`** → Add **labels** for the x-axis, y-axis, and a **title** for the graph.  
- **`plt.legend()`** → Displays a **legend** to differentiate between the two vectors.  
- **`plt.grid(True)`** → Adds a **grid** to improve readability.  
- **`plt.show()`** → Displays the generated graph.

*For qus 2:*

1. **Imports libraries**: `numpy` (for data generation), `seaborn` (for heatmap), and `matplotlib.pyplot` (for display).  
2. **Generates a 4×4 random matrix** with values between **0 and 1** using `np.random.rand(4, 4)`.  
3. **Defines row and column labels** (`A, B, C, D`) for better readability.  
4. **Creates a heatmap** using `sns.heatmap()`, with:  
   - **Annotated values** inside cells (`annot=True`).  
   - **Coolwarm colormap** (blue = low, red = high).  
   - **Thin grid lines** (`linewidths=0.5`).  
   - **Custom labels** for x and y axes.  
5. **Adds a title** and **displays the heatmap** using `plt.title()` and `plt.show()`.  

*For qus 3:*

1. **Imports libraries**: `numpy` (for matrix operations) and `matplotlib.pyplot` (for visualization).  
2. **Generates two random 4×4 matrices** (`A` and `B`) with integer values between **0 and 9**.  
3. **Performs matrix operations**:  
   - **Addition (`A + B`)**  
   - **Subtraction (`A - B`)**  
   - **Multiplication (`np.dot(A, B)`)** (dot product)  
4. **Flattens the matrices** into **1D arrays** for visualization.  
5. **Creates bar charts** for each matrix operation:  
   - **Addition (blue)**  
   - **Subtraction (black)**  
   - **Multiplication (red)**  
6. **Displays all three bar charts** in a single figure for easy comparison.  

 **Discussion**  

This code generates two **random 4×4 matrices** with integer values (0–9), performs **addition, subtraction, and multiplication**, and visualizes the results using **bar charts**.  

- **Matrix addition** (blue) shows element-wise sums.  
- **Matrix subtraction** (black) highlights differences, with possible negative values.  
- **Matrix multiplication** (red) computes the dot product, often resulting in larger values.  

## Concepts Covered
- Random number generation
- Data visualization with Matplotlib
- Matrix operations with NumPy
- Heatmap visualization
- Bar plot representation of matrix computations

## What I Learned
- How to generate and manipulate random numerical data in Python.
- Effective use of Matplotlib for visualizing mathematical operations.
- Understanding of matrix operations and their effects.
- How to present data using heatmaps and bar plots.
- Best practices for structuring a professional GitHub repository.



