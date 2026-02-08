# Adaptive Optimizers and Newton's Method

A comprehensive educational repository on numerical optimization concepts in machine learning, featuring detailed explanations, interactive visualizations, and mathematical foundations.

## 📚 Contents

This repository covers the evolution of optimization algorithms and their practical applications:

### Core Topics

1. **Gradient Descent Fundamentals**
   - Why fixed learning rates fail
   - Effects of learning rate selection
   - Convergence analysis

2. **Learning Rate Scheduling**
   - Step decay strategies
   - Exponential decay schedules
   - Cosine annealing techniques

3. **Adaptive Optimization Methods**
   - **AdaGrad**: Per-parameter learning rates
   - **RMSProp**: Moving average gradients
   - **Adam**: Momentum + Adaptive rates (industry standard)

4. **Optimization Theory**
   - Momentum and acceleration
   - Bias correction in early training
   - Second-order methods (Newton's Method)

5. **Computational Analysis**
   - Complexity comparison: $O(n)$ vs $O(n^3)$
   - Scalability for deep learning
   - Practical considerations

## 📁 Project Structure

```
Adaptive_Optimizers_and_Newtons_Method/
├── README.md
├── Adaptive_Optimizers_and_Newton_Method.ipynb
└── handwritten_notes.txt
```

## 🚀 Features

- **Interactive Visualizations**: Each concept includes 2D plots and convergence curves
- **Hands-On Demonstrations**: Code implementations showing how each optimizer works
- **Mathematical Rigor**: All equations properly formatted and explained
- **Practical Insights**: Tips for choosing the right optimizer for different problems
- **Comparison Tools**: Side-by-side analysis of different optimization strategies

## 📊 Notebook Highlights

The main notebook includes:

1. **Visualization 1**: Effect of different learning rates
2. **Visualization 2**: Learning rate scheduling strategies
3. **Visualization 3**: Sparse vs dense features problem
4. **Visualization 4**: How AdaGrad accumulates gradients
5. **Visualization 5**: AdaGrad vs RMSProp comparison
6. **Visualization 6**: Impact of β (beta) parameter
7. **Visualization 7**: Momentum vs no momentum
8. **Visualization 8**: Bias correction in Adam
9. **Visualization 9**: Optimizer comparison on different landscapes
10. **Visualization 10**: Newton's method vs gradient descent
11. **Visualization 11**: Computational complexity analysis

## 🎯 Quick Reference

| Optimizer | Best For | Complexity | Sparse Data | Deep Learning |
|-----------|----------|-----------|-------------|---------------|
| GD | Simple problems | $O(n)$ | ❌ | ❌ |
| RMSProp | Classical ML | $O(n)$ | ✅ | ⚠️ |
| **Adam** | **Deep Learning** | **$O(n)$** | **✅** | **✅✅✅** |
| Newton | Small problems | $O(n^3)$ | ❌ | ❌ |

## 💡 Key Takeaways

✅ **Use Adam by default** for deep neural networks  
✅ **Use RMSProp** for sparse data in classical ML  
✅ **Learning rate scheduling** improves convergence  
✅ **Bias correction** matters in early training steps  
✗ **Newton's method** is impractical for high dimensions  

## 🔧 Installation

No special installation required! Just:
```bash
git clone https://github.com/Aliha7ish/Adaptive_Optimizers_and_Newtons_Method.git
cd Adaptive_Optimizers_and_Newtons_Method
```

Then open the notebook with Jupyter:
```bash
jupyter notebook Adaptive_Optimizers_and_Newton_Method.ipynb
```

## 📖 How to Use

1. Open the notebook in Jupyter Lab or VS Code
2. Run cells in sequence to see visualizations
3. Modify hyperparameters to experiment
4. Study the explanations and equations
5. Review the key insights provided


## 🤝 Contributing

This is an evolving repository. You can add:
- Additional optimization algorithms
- Comparative studies on new datasets
- Implementation in different frameworks (PyTorch, TensorFlow)
- Real-world case studies

## 📚 References

- Kingma & Ba (2014): "Adam: A Method for Stochastic Optimization"
- Tieleman & Hinton (2012): "RMSProp"
- Duchi et al. (2011): "Adaptive Subgradient Methods"
- Boyd & Nocedal: "Numerical Optimization"

## 📧 Contact

Created as part of ITI Materials on Optimization  
Date: February 2026

---

**Happy Learning! 🚀**

All explanations focus on building intuition alongside mathematical rigor.
