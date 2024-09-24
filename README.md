# Global EV Sales Analysis: 2010-2024

This project analyzes the global sales and adoption trends of Electric Vehicles (EVs) from 2010 to 2024. The analysis explores the distribution of EV stock share and sales across different regions and powertrain types, providing insights into the evolving landscape of the global EV market.

## Project Overview

Electric Vehicles (EVs) are transforming the transportation sector, offering a sustainable alternative to traditional internal combustion engine (ICE) vehicles. This project delves into the global EV market, highlighting key trends and insights:

- **Regional Comparison**: Identify leading and lagging regions in EV adoption.
- **Powertrain Analysis**: Examine the growth of different EV powertrain types (BEV, PHEV, etc.) over time.
- **Trend Analysis**: Analyze year-over-year growth rates in EV stock and sales share.

## Dataset

The dataset used in this project is sourced from the [International Energy Agency (IEA) - Global EV Data 2024](https://www.iea.org/data-and-statistics/data-product/global-ev-outlook-2024#global-ev-data). It includes historical data on EV stock share, sales, and other relevant metrics across various regions and powertrain types.

## Project Structure

- **notebooks/Global-EV-Sales-Analysis.ipynb**: Jupyter Notebook containing the analysis and visualizations.
- **data/**: Folder containing the dataset used for analysis.
- **README.md**: Project description and instructions.
- **requirements.txt**: List of dependencies required to run the project.

## Key Insights

1. **Regional Dynamics**: Europe and Asia lead in EV adoption, reflecting strong policy support and consumer demand.
2. **Powertrain Trends**: Battery Electric Vehicles (BEVs) show the highest growth, driven by advancements in battery technology and reduced costs.
3. **Market Evolution**: The global EV market shows a steady increase in sales and stock share, indicating a positive outlook for future growth.

## Visualizations

### 1. EV Sales Over Time
![output_14_0](https://github.com/user-attachments/assets/f1dce030-98a3-4ec5-b90e-061ba38090cd)

This line plot shows the growth of EV sales over the years, highlighting the increasing adoption of electric vehicles globally.

### 2. Distribution of EV Share By Region
![output_14_0](https://github.com/user-attachments/assets/4e623c69-b98e-4d82-8c2c-8a33ca0e2ca1))

This bar chart illustrates the average EV stock share across different regions, showcasing which areas are leading in EV adoption.

### 3. Correlation between EV Stock Share and EV Sales Share

![output_28_0](https://github.com/user-attachments/assets/f23c4f78-29a0-4cd0-9cc7-5b647c6f1e49)

This histogram displays the distribution of EV sales, providing insights into the common sales volumes and the overall spread of the data.

## How to Run the Project

1. Clone the repository:
  ```bash!
  git clone https://github.com/your-username/Global-EV-Sales-Analysis.git
  ```

2. Navigate to the project directory:
  ```bash
  cd Global-EV-Sales-Analysis
  ```

3. Install the required packages:
  ```bash
  pip install -r requirements.txt
  ```

4. Open the Jupyter Notebook to explore the analysis:
  ```bash
  jupyter notebook notebooks/Global-EV-Sales-Analysis.ipynb
  ```

## Dependencies

The project requires the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn

These are listed in the `requirements.txt` file for easy installation.

## Acknowledgements

- Data Source: [International Energy Agency (IEA) - Global EV Data 2024](https://www.iea.org/data-and-statistics/data-product/global-ev-outlook-2024#global-ev-data).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
