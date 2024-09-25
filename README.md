
# COVID-19: Pandemic Patterns

This project provides a set of scripts for visualizing COVID-19 data using Python. The project includes several Python files organized under the `FINAL` folder and is designed to generate insights through visual representations of COVID-19 data.

![pandemic patterns image](https://github.com/user-attachments/assets/0ccbd00b-6ad9-49a7-9771-f24304032eb6)

## Project Structure

```
.
├── FINAL/
│   ├── data_wrangling.py
│   ├── final_testing.py
│   ├── modified_tree_FINAL.py
├── main.py
├── requirements.txt
└── README.md
```

### Files

- `main.py`: The entry point to the project. This script imports modules from the `FINAL` folder and executes the `covid_visualisation()` function, which generates the visualizations for the COVID-19 data.
- `FINAL/data_wrangling.py`: Contains functions and logic for cleaning and preparing the COVID-19 dataset for analysis.
- `FINAL/final_testing.py`: This file defines the `covid_visualisation()` function, which is responsible for creating the visual representations of the data.
- `FINAL/modified_tree_FINAL.py`: Likely contains tree-related data structures or algorithms used in the project, though specific details would require further review.
- `requirements.txt`: Lists all the Python packages required to run the project.

## How to Run the Project

1. Install the required Python dependencies by using the following command:
   ```
   pip install -r requirements.txt
   ```

   The `requirements.txt` file includes dependencies like:
   - `python_ta`: Used for type checking and contract validation.
   - `python_ta.contracts`: Used to check contracts within the codebase.
   - Any other libraries used for data processing, visualization, or analysis.

2. Once dependencies are installed, you can run the `main.py` script to execute the project:
   ```bash
   python main.py
   ```

## Features

- **Data Wrangling**: The script in `data_wrangling.py` prepares and cleans raw COVID-19 data for visualization.
- **COVID-19 Data Visualization**: The `covid_visualisation()` function in `final_testing.py` generates visual outputs based on the processed data.
- **Code Contracts and Type Checking**: The project uses `python_ta.contracts` to enforce code contracts, ensuring that function inputs and outputs conform to expected types and behaviors.

## Requirements

Make sure to install the dependencies listed in the `requirements.txt` file before running the project. Use the following command to install them:

```bash
pip install -r requirements.txt
```

This will run any `doctest`-style tests embedded in your functions.

## License

This project is licensed under the MIT License.
