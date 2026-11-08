# 🚢 Titanic Survival Analysis

## 📖 Project Description

This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset to understand the factors that influenced passenger survival. It explores and cleans the data using Pandas, then uses Matplotlib and Seaborn to create visualizations of survival rates by passenger class, gender, age group, and port of embarkation.

The dataset (`titanic.csv`) contains **891 passengers** and **15 columns**, including survival status, passenger class, gender, age, fare, and port of embarkation.

## ✨ Features

- 📥 Loads the Titanic dataset from a CSV file
- 🔍 Explores the data: shape, info, missing values, and statistical summary
- 🧹 Cleans the data: fills missing values and removes the `deck` column
- 🆕 Creates new columns: `age_group`, `family_size`, and `sex_num`
- 📊 Calculates survival rates by class, gender, age group, port, and class + gender
- 📈 Creates visualizations:
  - Overall survival count
  - Survival rate by passenger class
  - Survival rate by gender
  - Survival rate by class and gender
  - Age distribution by survival
  - Survival rate by age group
  - Survival rate by port of embarkation
  - Correlation heatmap
- 🖼️ Saves all charts together in a single image
- 📝 Summarizes the key findings

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| 🐍 Python | Programming language |
| 🐼 Pandas | Data manipulation and analysis |
| 📉 Matplotlib | Data visualization |
| 🎨 Seaborn | Statistical visualization |
| 📓 Jupyter Notebook | Interactive coding environment |
| 🔧 Git | Version control |
| 🐙 GitHub | Code hosting and project sharing |

## ⚙️ How to Run / Installation

1. **Download the project folder** from GitHub (Code → Download ZIP), extract it, and open the folder in your terminal
   ```bash
   cd Titanic_Survival_Analysis
   ```

2. **Install the required libraries**
   ```bash
   pip install pandas matplotlib seaborn jupyter
   ```

3. **Open Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. **Run the project**
   - Open `main.ipynb`
   - Click **Kernel → Restart & Run All** (or run each cell with `Shift + Enter`)

> 💡 Keep `titanic.csv` in the same folder as `main.ipynb`.

## 📁 Project Structure

```
├── 📓 main.ipynb      # Complete project code
├── 📄 titanic.csv     # Titanic dataset
├── 🖼️ output.png      # Project output
└── 📝 README.md       # Project documentation
```

## 📸 Output
![Program Output](output.png)


## 👩‍💻 Author

**Kajal Mahato**
