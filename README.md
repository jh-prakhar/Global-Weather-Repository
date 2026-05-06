# Global-Weather-Repository
# Global Weather Trend Forecasting
**Assessment for PM Accelerator**

** Dataset
The dataset is available on the Kaggle website. 
World Weather Repository: https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository/code

## PM Accelerator Mission
To promote and advance the field of Product Management through education, networking, and career development, empowering professionals to excel in their roles and drive innovation in their organizations.

## Project Overview
This project analyzes the `GlobalWeatherRepository.csv` dataset to forecast weather trends and identify environmental patterns. It covers data cleaning, exploratory data analysis (EDA), and the implementation of a machine learning ensemble to predict perceived temperatures ("Feels Like").

## Tech Stack
- **Language:** Python 3.x
- **Environment:** Jupyter Lab / Google Colab
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

## Key Findings
- **Feature Importance:** Temperature and Humidity were the strongest predictors for the "Feels Like" metric.
- **Environmental Impact:** Identified a positive correlation between humidity and specific air quality indices.
- **Model Performance:** The Random Forest Regressor achieved an R2 score of 0.99, indicating high predictive accuracy.

## How to Run
1. Clone this repository: `git clone <your-repo-url>`
2. Install dependencies: `pip install -r requirements.txt`
3. Open `weather_analysis.ipynb` in Jupyter Lab.
4. Run all cells to generate analysis and visualizations.

## Repository Structure
- `GlobalWeatherRepository.csv`: The source dataset.
- `weather_analysis.ipynb`: Main analysis notebook.
- `requirements.txt`: List of necessary Python packages.
- `demo_video_link.md`: Link to the project walkthrough video.

