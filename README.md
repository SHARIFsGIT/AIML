# AI & Machine Learning Learning Repository

A comprehensive educational repository containing structured course materials for learning Python programming, data science, and machine learning concepts. This project provides hands-on Jupyter notebooks covering everything from Python fundamentals to advanced machine learning algorithms.

## Table of Contents

- [Overview](#overview)
- [Technology Stack](#technology-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Learning Path](#learning-path)
- [Course Content](#course-content)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Contributing](#contributing)

## Overview

This repository serves as a complete learning path for AI and Machine Learning, designed for beginners progressing to intermediate practitioners. It combines theoretical concepts with practical, hands-on exercises using real-world datasets and scenarios.

**What You'll Learn:**
- Python programming fundamentals for ML
- Functional programming concepts
- NumPy and Pandas for data manipulation
- Data visualization with Matplotlib and Seaborn
- Statistical analysis and descriptive statistics
- **Data preprocessing and feature engineering**
- **Machine learning pipeline construction**
- **Real-world data handling strategies**
- **Domain knowledge integration in ML**
- Machine learning algorithms and concepts
- Deep learning with TensorFlow and Keras

## Technology Stack

- **Python 3.x** - Primary programming language
- **Jupyter Notebook/Lab** - Interactive development environment
- **NumPy** - Numerical computing
- **Pandas** - Data manipulation and analysis
- **Matplotlib & Seaborn** - Data visualization
- **TensorFlow 2.20.0 & Keras 3.12.0** - Deep learning frameworks
- **Scikit-learn 1.7.2** - Machine learning algorithms
- **SciPy 1.16.3** - Scientific computing

## Project Structure

```
AIML/
├── Python For ML/              # Python fundamentals for Machine Learning
│   ├── Week 01/               # Python basics and control flow
│   │   ├── Mod 01/           # List comprehensions, advanced patterns
│   │   ├── Mod 01.1/         # Input/output, basic problems
│   │   ├── Mod 02/           # Control flow, conditionals
│   │   └── Mod 03-05.ipynb   # Arrays, exercises, practice
│   │
│   ├── Week 02/               # Functional programming
│   │   ├── Mod 06.ipynb      # Generators, functional programming
│   │   ├── Mod 07.ipynb      # Lambda, map, filter, reduce
│   │   └── Mod 08-09.ipynb   # Advanced functional concepts
│   │
│   ├── Week 03/               # NumPy and Pandas
│   │   ├── Mod 10.ipynb      # NumPy arrays, creation, operations
│   │   ├── Mod 11.ipynb      # Array indexing, slicing
│   │   ├── Mod 12.ipynb      # Advanced NumPy
│   │   ├── Mod 13.ipynb      # Pandas DataFrames
│   │   └── Practice week 3.5.ipynb  # Hands-on exercises
│   │
│   └── Week 04/               # Data Visualization
│       ├── Mod 14.ipynb      # Matplotlib fundamentals
│       ├── Mod 15.ipynb      # Data visualization techniques
│       ├── Mod 16.ipynb      # Advanced visualization
│       └── Mod 17.ipynb      # Final concepts
│
└── Machine Learning/          # ML algorithms and statistical analysis
    ├── Week 01/               # Statistical analysis fundamentals
    │   ├── Extra Practice Problem Module 01.ipynb  # Statistical measures
    │   └── Mod 2.5.ipynb     # Machine learning concepts
    │
    ├── Week 02/               # Descriptive statistics and visualization
    │   ├── Mod 03.ipynb      # Range, variance, standard deviation
    │   ├── Mod 04.ipynb      # Quartiles, percentiles, and IQR
    │   ├── Mod 05.ipynb      # Data visualization with Matplotlib
    │   ├── Mod 06.ipynb      # Advanced visualization techniques
    │   └── Mod 07.ipynb      # Box plots and outlier analysis
    │
    └── Week 03/               # Data preprocessing and feature engineering
        ├── Mod 08.ipynb      # Statistical measures calculations
        ├── Mod 09.ipynb      # Comprehensive data preprocessing pipeline
        └── README.md         # Module 09 detailed documentation
```

**Total:** 34 Jupyter notebooks organized across multiple weeks

## Getting Started

### Prerequisites

- Python 3.9 or higher
- pip (Python package manager)
- 2GB+ available disk space

### Installation

1. **Clone or download this repository:**
   ```bash
   cd P:\AIML
   ```

2. **Create a virtual environment (if not already created):**
   ```bash
   python -m venv venv
   ```

3. **Activate the virtual environment:**

   **Windows:**
   ```bash
   .\venv\Scripts\activate
   ```

   **macOS/Linux:**
   ```bash
   source venv/bin/activate
   ```

4. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

5. **Launch Jupyter:**
   ```bash
   jupyter lab
   ```
   or
   ```bash
   jupyter notebook
   ```

## Learning Path

### Recommended Progression

#### Phase 1: Python Fundamentals (Week 01)
Start here if you're new to Python or need a refresher:
- Input/output operations
- Control flow (if/else, loops)
- Lists, arrays, and strings
- List comprehensions
- Problem-solving exercises

**Start with:** `Python For ML/Week 01/Mod 01.1/1.1-3 Taking Input in Python.ipynb`

#### Phase 2: Functional Programming (Week 02)
Learn functional programming paradigms:
- Generators and iterators
- Lambda functions
- Map, filter, reduce operations
- Functional programming best practices

**Start with:** `Python For ML/Week 02/Mod 06.ipynb`

#### Phase 3: Data Manipulation (Week 03)
Master NumPy and Pandas:
- NumPy array creation and manipulation
- Array indexing, slicing, fancy indexing
- Data types and type conversion
- Pandas DataFrames
- Data filtering, sorting, and grouping

**Start with:** `Python For ML/Week 03/Mod 10.ipynb`

#### Phase 4: Data Visualization (Week 04)
Learn to visualize data effectively:
- Matplotlib plotting
- Seaborn visualizations
- Data visualization best practices

**Start with:** `Python For ML/Week 04/Mod 14.ipynb`

#### Phase 5: Machine Learning (Ongoing)
Apply your skills to machine learning:

**Phase 5a: Statistical Foundations (Week 01)**
- Statistical measures and analysis
- Outlier detection
- Machine learning concepts

**Start with:** `Machine Learning/Week 01/Extra Practice Problem Module 01.ipynb`

**Phase 5b: Descriptive Statistics & Visualization (Week 02)**
- Range, variance, and standard deviation
- Quartiles, percentiles, and IQR
- Data visualization techniques
- Box plots and outlier analysis

**Start with:** `Machine Learning/Week 02/Mod 03.ipynb`

**Phase 5c: Data Preprocessing & Feature Engineering (Week 03)**
- Missing value handling strategies
- Categorical variable encoding
- Feature scaling and normalization
- Outlier detection and handling
- Feature engineering techniques
- Building ML pipelines

**Start with:** `Machine Learning/Week 03/Mod 08.ipynb`

## Course Content

### Python For ML

#### Week 01: Python Basics
- Input/output operations
- Control structures (if/else, loops)
- Data structures (lists, arrays, strings)
- List comprehensions and advanced patterns
- Codeforces competitive programming problems

#### Week 02: Functional Programming
- Generators and iterators
- Lambda functions
- Map, filter, reduce
- Functional programming paradigms

#### Week 03: NumPy & Pandas
- NumPy arrays and operations
- Array indexing and slicing
- Random array generation
- Pandas DataFrames
- Real-world data analysis (student marks, employee data, weather analysis)

#### Week 04: Data Visualization
- Matplotlib plotting techniques
- Seaborn statistical visualizations
- Chart types (line, bar, scatter, histogram, etc.)
- Customization and styling

### Machine Learning

#### Week 01: Statistical Analysis
- Descriptive statistics (range, variance, standard deviation)
- Quartiles and interquartile range (IQR)
- Outlier detection methods
- Data distribution analysis
- Machine learning concepts and fundamentals

#### Week 02: Descriptive Statistics & Visualization
- **Range, Variance, and Standard Deviation**: Mathematical calculations and interpretations
- **Quartiles, Percentiles, and IQR**: Position-based statistics and outlier detection
- **Data Visualization with Matplotlib**: Creating charts and plots for statistical analysis
- **Advanced Visualization Techniques**: Multiple subplot layouts and complex visualizations
- **Box Plots and Outlier Analysis**: Visual identification of outliers and data distribution

#### Week 03: Data Preprocessing & Feature Engineering
- **Statistical Measures Calculations**: Practical implementation of descriptive statistics
- **Comprehensive Data Preprocessing Pipeline**:
  - Missing value handling (median, mode, column dropping)
  - Categorical encoding (label encoding, one-hot encoding)
  - Feature scaling (StandardScaler, MinMaxScaler)
  - Outlier detection and handling (IQR method, removal, capping, log transformation)
  - Feature engineering (polynomial features, binning, domain-driven features)
  - ML pipeline construction with ColumnTransformer
- **Real-world Datasets**: Titanic dataset and Heart Disease dataset
- **Production-ready workflows**: Complete end-to-end preprocessing with detailed explanations

**Key Features of Week 03:**
- Beginner-friendly explanations with "why" behind each technique
- Clinical context for medical datasets
- Comparison of different approaches with pros/cons
- Pipeline implementation to prevent data leakage
- Comprehensive documentation for each preprocessing step

## Dependencies

### Core Data Science Libraries
- numpy==2.3.4
- pandas==2.3.3
- scipy==1.16.3
- scikit-learn==1.7.2

### Deep Learning
- tensorflow==2.20.0
- keras==3.12.0
- tensorboard==2.20.0

### Visualization
- matplotlib==3.10.7
- seaborn==0.13.2
- matplotlib-venn==1.1.2

### Jupyter Environment
- jupyter==1.1.1
- jupyterlab==4.4.10
- notebook==7.4.7
- ipython==9.7.0
- ipykernel==7.1.0

### Additional Tools
- beautifulsoup4==4.14.2 (web scraping)
- requests==2.32.5 (HTTP requests)
- pillow==12.0.0 (image processing)
- h5py==3.15.1 (data storage)

For a complete list of dependencies, see `requirements.txt` (140 packages total).

## Usage

### Running Notebooks

1. Ensure your virtual environment is activated
2. Launch Jupyter Lab or Notebook
3. Navigate to the desired notebook
4. Run cells sequentially (Shift + Enter)

### Practice Problems

Each week includes `.5` modules (e.g., Mod 07.5, Mod 11.5) containing additional practice problems. These are designed to reinforce concepts learned in the main modules.

### Real-World Scenarios

The notebooks include practical exercises with real-world applications:
- Student marks analyzer
- Warehouse weight calculations
- Temperature and weather reports
- Traffic data analysis
- Employee data filtering
- Sales and business analytics
- **Week 03 Special**: Real-world medical datasets (Titanic survival prediction, Heart disease classification)
- **Week 03**: Clinical data preprocessing with domain knowledge application

## Contributing

This is an educational repository. If you're using these materials:

1. Work through notebooks sequentially
2. Complete all practice problems
3. Experiment with the code
4. Try solving Codeforces problems linked in Week 01
5. Apply concepts to your own datasets

## Tips for Success

1. **Sequential Learning:** Follow the weeks in order - each builds on previous concepts
2. **Hands-on Practice:** Don't just read - run every code cell and experiment
3. **Practice Problems:** Complete all `.5` modules for reinforcement
4. **Real Data:** Try applying techniques to your own datasets
5. **Take Notes:** Document your learning in markdown cells
6. **Ask Questions:** Research concepts you don't understand

## Support

For issues with:
- **Environment setup:** Check Python version and virtual environment activation
- **Package installation:** Ensure pip is up to date (`pip install --upgrade pip`)
- **Jupyter issues:** Try both `jupyter lab` and `jupyter notebook`
- **Code errors:** Read error messages carefully and check for typos

---

Happy Learning! Start your AI/ML journey today.
