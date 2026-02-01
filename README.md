# Linear Equation Calculator 📐

A Python program that calculates slope, intercepts, and visualizes linear equations with interactive graphs.

## 🎯 Features

- **Calculate slope** from equation format y = mx + b
- **Find x-intercept** (where the line crosses the x-axis)
- **Find y-intercept** (where the line crosses the y-axis)
- **Visual graphing** with matplotlib
- **Interactive input** for any linear equation
- **Marked intercept points** on the graph

## 📊 Example Output

For the equation **y = 2x - 2**:
```
=== LINEAR EQUATION CALCULATOR ===
Equation: y = 2x + -2

Slope (m): 2
Y-intercept: -2
Point: (0, -2)
X-intercept: 1.0
Point: (1.0, 0)
```

Plus a graph showing the line with both intercepts marked in red!

## 🚀 How to Use

### Basic Version
```python
python linear_calc.py
```

Enter your slope (m) and y-intercept (b) when prompted.

### What You'll Get
1. Calculated slope
2. Y-intercept with coordinates
3. X-intercept with coordinates  
4. Visual graph with the line plotted
5. Grid and axes for easy reading

## 🛠️ Installation

### Requirements
- Python 3.x
- matplotlib library

### Install matplotlib
```bash
pip install matplotlib
```

## 💡 What I Learned

- Working with linear equations programmatically
- Using **matplotlib** for data visualization
- Creating interactive command-line programs
- Mathematical problem-solving with Python
- Plotting graphs with custom styling
- Marking specific points on graphs

## 📚 Math Behind It

For any linear equation **y = mx + b**:

- **Slope (m):** The coefficient of x
- **Y-intercept:** Value when x = 0 → Point: (0, b)
- **X-intercept:** Value when y = 0 → Solve: 0 = mx + b → x = -b/m

## 🎨 Technical Details

**Language:** Python 3.14.2
**Libraries:** matplotlib.pyplot  
**Concepts:** Linear algebra, coordinate geometry, data visualization

## 🔮 Future Improvements

- [ ] Support for quadratic equations
- [ ] Multiple equations on one graph
- [ ] Save graphs as image files
- [ ] Show step-by-step solution
- [ ] Calculate distance between two points
- [ ] Find equation from two points

## 📸 Screenshots

*Graph shows:*
- Linear equation plotted across x-range
- Red dots marking both intercepts
- Grid for easy reading
- Labeled axes

---

**Built:** February 2026  
**Project Type:** Math & Visualization  
**Part of:** Learning Python for AI × Economics  
**Next Project:** Stock price tracker with real-time data
