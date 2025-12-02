# 📊 Gradient Descent Optimization Dashboard
This Power BI dashboard visualizes how learning rates and iterations affect the performance of a Multivariate Linear Regression model trained from scratch using Gradient Descent.
It helps understand model convergence, R² score behavior, and hyperparameter tuning impact on training stability and accuracy.

## ✨ Features
- Interactive line charts showing R² vs learning rate and iterations.
- Smooth performance curves generated from 200+ interpolated values.
- Heatmaps visualizing correlation and training metrics.
- Neon-style color theme for clear visualization on a dark background.
- Designed for insight into Gradient Descent optimization.
## 📋 Prerequisites
Before using this dashboard, ensure you have:
- Power BI Desktop (latest version recommended)
- Python 3.8+ (for generating CSV data)
- Pandas + NumPy + Matplotlib (optional, if regenerating data)
## 🚀 Getting Started
1. Clone the repository:
```bash
git clone https://github.com/radwanhefny/Gradient-Descent-Optimization-Dashboard.git
cd Gradient-Descent-Optimization-Dashboard

```
2. Open the PBIX file in Power BI Desktop:
```bash
Gradient_Descent_Optimization_Dashboard.pbix
```
3. Explore the interactive dashboard:
- Hover over lines for R² values.
- Use slicers to filter by iterations or learning rates.
- Analyze the effect of hyperparameter tuning visually.
- 
## 🎬 Screenshots / Demo

📈 R² vs Learning Rate & Iterations

Visualizes model performance and convergence.
<img src="https://github.com/radwanhefny/radwanhefny/blob/main/photos/data%20analysis/multivariate%20LR.jpg" width="500"/>





## 🗂️ Project Structure
```
Gradient-Descent-Optimization-Dashboard/
├── Gradient_Descent_Optimization_Dashboard.pbix  # Power BI dashboard
├── smooth_curve_data.csv                         # Interpolated LR/R² values
├── README.md
└── images/
      └── multivariate_LR.jpg                    # Dashboard screenshot





```
## 🛠️ Usage
- Open PBIX file in Power BI Desktop.
- Interact with visuals to explore training behavior.
- Optional: regenerate smooth curves using Python scripts if included.

## ✅ Evaluation Metrics
- R² Score (main metric visualized in the dashboard).
- Visual inspection of convergence trends for different learning rates and iterations.
- 
## 🧠 How It Works
1. Generates model predictions for multiple learning rates and iterations.
2. Calculates R² scores to measure performance.
3. Interpolates values for smooth curve visualization.
4. Plots interactive line charts and heatmaps in Power BI.

## 🤝 Contributing
Contributions are welcome!
1. Fork the repository
2. Create a new feature branch
3. Submit a pull request
Please ensure your code is clean, structured, and well-commented.
## 📝 License
This project is licensed under the MIT license - see the LICENSE file for details. 
## 📞 Support
If you have questions or need help, feel free to:
- Open an issue on this repository  
- Connect with me on LinkedIn: https://www.linkedin.com/in/radwanhefny  
