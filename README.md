# Data Visualization with World Happiness Dataset 📊

A comprehensive Jupyter notebook tutorial demonstrating various data visualization techniques using Python's most popular visualization libraries: Pandas, Matplotlib, and Seaborn. This project uses the World Happiness Report 2019 dataset to showcase practical examples of exploratory data analysis through visualizations.

## 📖 Overview

This repository contains a detailed tutorial on data visualization techniques essential for exploratory data analysis. Through the World Happiness Dataset, you'll learn how to create and customize various types of plots to extract meaningful insights from data.

## ✨ Key Features

### Visualization Techniques Covered

- **Univariate Analysis**
  - Histograms for continuous variables
  - Count plots for categorical variables
  
- **Bivariate Analysis**
  - Scatter plots
  - Joint plots
  
- **Multivariate Analysis**
  - Correlation matrices with heatmaps
  - Scatter plot matrices (SPLOM)
  - Pair plots

- **Distribution Analysis**
  - Box plots for outlier detection
  - Violin plots for distribution visualization
  - Bee swarm plots for detailed data point distribution

### Three Implementation Approaches

Each visualization type is demonstrated using three different libraries:
1. **Pandas** - Built-in plotting capabilities
2. **Matplotlib** - Low-level plotting with full customization
3. **Seaborn** - High-level statistical visualizations

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib** - Core plotting library
- **Seaborn** - Statistical data visualization

## 📦 Installation

### Prerequisites

Ensure you have Python 3.x installed on your system.

### Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/DataDarling/Data-Visualization-World-Happiness-Dataset.git
cd Data-Visualization-World-Happiness-Dataset
```

2. Install required packages:
```bash
pip install numpy pandas matplotlib seaborn jupyter
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook data_visualization.ipynb
```

## 📊 Dataset Information

### World Happiness Report 2019

The notebook uses the World Happiness Report 2019 dataset, which includes:

- **Overall Rank**: Country ranking based on happiness score
- **Country**: Country name
- **Score**: Happiness score
- **GDP per capita**: Economic indicator
- **Social Support**: Social relationships metric
- **Healthy life expectancy**: Health metric
- **Freedom to make life choices**: Freedom indicator
- **Generosity**: Giving behavior metric
- **Perceptions of corruption**: Trust in government

**Dataset Location**: `./data/world_happiness_2019.csv`

**Source**: [World Happiness Report](https://worldhappiness.report/)

## 🚀 Usage

The notebook is organized into clear sections:

1. **Introduction**: Overview of visualization importance and tools
2. **Whole Dataset Analysis**: Correlation matrices and scatter plot matrices
3. **Single Feature Analysis**: Histograms, box plots, violin plots, and swarm plots
4. **Two Feature Analysis**: Scatter plots and joint plots

### Running the Notebook

Simply open `data_visualization.ipynb` in Jupyter Notebook and run the cells sequentially. Each section contains:
- Explanatory markdown with function references
- Working code examples
- Visual output demonstrations

## 📚 Learning Objectives

By working through this notebook, you will learn:

- How to choose the right visualization for your data type
- The differences between Pandas, Matplotlib, and Seaborn approaches
- Best practices for exploratory data analysis
- How to detect outliers using box and violin plots
- How to visualize relationships between variables
- How to customize plots with colors, styles, and themes
- How to create publication-ready visualizations

## 🎨 Visualization Examples

The notebook demonstrates:

- **Correlation Matrix Heatmaps**: Understand relationships between all numeric features
- **Scatter Matrices**: Visualize pairwise relationships in the dataset
- **Distribution Plots**: Understand the spread and shape of your data
- **Categorical Analysis**: Compare groups and categories
- **Multi-dimensional Plots**: Explore complex relationships with color, size, and style encodings

## 🔗 Useful Resources

The notebook includes links to:
- [Matplotlib Named Colors](https://matplotlib.org/3.1.0/gallery/color/named_colors.html)
- [Matplotlib Colormaps](https://matplotlib.org/stable/tutorials/colors/colormaps.html)
- [Seaborn Color Palettes](https://seaborn.pydata.org/tutorial/color_palettes.html)
- [Pandas Plotting Documentation](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.plot.html)
- [Matplotlib Plot Types](https://matplotlib.org/stable/plot_types/index)
- [Seaborn Gallery](https://seaborn.pydata.org/examples/index.html)

## 🤝 Contributing

Contributions are welcome! If you'd like to improve this tutorial:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add new visualization example'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## 📝 License

This project is open source and available for educational purposes.

## 👤 Author

**DataDarling**

- GitHub: [@DataDarling](https://github.com/DataDarling)

## 🙏 Acknowledgments

- World Happiness Report team for providing the dataset
- The open-source community for the amazing visualization libraries
- Contributors who help improve this educational resource

---

⭐ If you find this tutorial helpful, please consider giving it a star!

**Happy Visualizing!** 📈
