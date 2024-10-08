
# Nobel Laureates Analysis Project

This project analyzes Nobel Laureates data using the dataset from [Kaggle](https://www.kaggle.com/datasets/nobelfoundation/nobel-laureates). The analysis includes trends, distributions, and key insights related to Nobel Prize winners over the years.

## Dataset

The dataset contains information about Nobel Prize winners, including:
- Name of the laureate
- Category of the prize (e.g., Physics, Chemistry, Peace)
- Year of award
- Birthdate, Birthplace
- Motivation for the award
- Gender, Organization, Country

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/nobel-laureates-analysis.git
    ```

2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

Once you have the necessary dependencies installed, you can run the analysis script to generate visualizations and insights.

```bash
python nobel_analysis.py
```

The analysis script will:
- Load and clean the Nobel Laureates dataset.
- Perform exploratory data analysis (EDA) including:
    - Distribution of awards across years.
    - Trends in laureates' birth countries and organizations.
    - Gender distribution among laureates.
- Generate visualizations showing trends and key insights.

## Project Structure

- `nobel_analysis.py`: Main Python script for data analysis and visualization.
- `data/`: Contains the Nobel Laureates dataset (download from Kaggle and place here).
- `visualizations/`: Folder for storing generated plots and figures.
- `requirements.txt`: List of dependencies required to run the project.

## Credits

Dataset from [Nobel Prize](https://www.kaggle.com/datasets/nobelfoundation/nobel-laureates) provided by the Nobel Foundation on Kaggle.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
