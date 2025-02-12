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


