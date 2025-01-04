# FIFA World Cup Data Mining

## Overview
This repository contains a comprehensive data mining project focused on FIFA World Cup events. The project utilizes various datasets to explore and analyze different aspects of World Cup history, including attendance, goals, matches, and tournaments.

## Dataset
The project is based on two main datasets:
1. [The Fjelstul World Cup Database](https://github.com/jfjelstul/worldcup)
2. [World Cup Attendance Dataset](https://drive.google.com/file/d/1-4FNJB6T5LMpSMOtPv3WIa7nOjTFAC3z/view)

the datasets are provided in the data folder.

## Technologies Used
- Language: Python
- Libraries: Numpy, Scipy, Pandas, Matplotlib, Plotly, Scikit-Learn
- IDE: Jupyter Notebook, Google Colab

## Project Structure
The project is divided into several main sections:

1. **Data Cleaning and Integration**
   - Merging attendance dataset with the Fjelstul dataset
   - Creating a new dataframe for players and their represented teams

2. **Feature Engineering**
   - Creating new features such as total goals, host team indicator, capacity ratio, etc.
   - Discretization of attendance and capacity ratio features

3. **Exploration and Analysis**
   - Attendance Case Study
   - Goals Case Study
   - Matches Case Study
   - Tournament Case Study

## Key Findings
- Attendance patterns and trends across World Cup history
- Goal scoring statistics and trends
- Analysis of top goal scorers and tournament goal trends
- Frequency analysis of matches between teams
- Insights into players representing multiple teams
- Relationships between host countries, tournament winners, and attendance

## How to Use
1. Clone this repository 
   ````bash
   git clone https://github.com/Monzer-Hw/World-Cup-Events
   ````
2. Install `uv` on your machine
   
   For macOS and linux:
   ````bash
   curl -LsSf https://astral.sh/uv/install.sh | sh
   ````
   For windows:
   ````bash
   powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
   ````
3. Run the following commands:
   
   To create a virtual environment with the required libraries:
   ````bash
   uv sync
   ````

   To create a kernel for the jupyter notebook:
   ````bash
   uv run ipython kernel install --user --name=world-cup-events
   ````
4. Run the jupyter notebook with this command:
   ````bash
   uv run --with jupyter jupyter lab
   ````
   Or just select the virtual environment and run the notebook if you have VS Code with jupyter extentios
