# Outbreaks and Recalls

This project was made to explore potential correlations between foodborne illness outbreaks recorded by the CDC in the National Outbreak Reporting System (NORS) and food product recalls published through the FDA Recall API.

The goal is to determine whether patterns in FDA recalls align with outbreak trends over time, geography, and reason for recalls/type of illness outbreak.
# Outbreaks and Recalls

This project was made to explore potential correlations between foodborne illness outbreaks recorded by the CDC in the National Outbreak Reporting System (NORS) and food product recalls published through the FDA Recall API.

The goal is to determine whether patterns in FDA recalls align with outbreak trends over time, geography, and reason for recalls/type of illness outbreak.


## How to Use
1. Clone this repository via GitHub.

2. Install the required Python packages:  
   pip install -r requirements.txt

3. Open `outbreak_recall.ipynb` in Jupyter Notebook.

4. Run all cells
- Notebook will load and clean data, gather recall data from API, store data in SQLite databases, allow recall searches by state and date, as well as generate visualizations.
## Data Sources
FDA food recall API link: https://open.fda.gov/apis/food/enforcement/
- Provides official FDA food product recall records, including recall initiation dates, distribution patterns, product descriptions, and recall classifications.

CDC NORS database stored in data folder, originated from: https://data.cdc.gov/Foodborne-Waterborne-and-Related-Diseases/NORS/5xkq-dg7x/about_data
-  reported foodborne illness outbreak data.
## Author

Rayna (Nox) Shake- [@NoxRainTempest](https://www.github.com/NoxRainTempest)


## Features

- SQLite databases for efficient querying
- Search recalls by state and recall initiation date range
- Pandas based analysis
- Notebook friendly, reproducible workflow


## Requirements
- Python 3.9+
- Jupyter Notebook
- Required packages listed in requirements.txt

## Notes

- Recall initiation dates are stored in YYYY-mm format as strings.
- Distribution patterns may include multiple states, regions, or nationwide labels.
- This project is exploratory and does not imply causation between recalls and outbreaks.
## Findings

As of my most recent commits, Ive found that there does not seem to be much correlation between FDA food recalls and reported foodborne disease outbreaks from the CDC. While I had anticipated more proof of a potential correlation, it also makes sense that there wasn't as the FDA recalls are done in part to limit the spread of foodborne illnesses.


## How to Use
1. Clone this repository via GitHub.

2. Install the required Python packages:  
   pip install -r requirements.txt

3. Open `outbreak_recall.ipynb` in Jupyter Notebook.

4. Run all cells
- Notebook will load and clean data, gather recall data from API, store data in SQLite databases, allow recall searches by state and date, as well as generate visualizations.
## Data Sources
FDA food recall API link: https://open.fda.gov/apis/food/enforcement/
- Provides official FDA food product recall records, including recall initiation dates, distribution patterns, product descriptions, and recall classifications.

CDC NORS database stored in data folder, originated from: https://data.cdc.gov/Foodborne-Waterborne-and-Related-Diseases/NORS/5xkq-dg7x/about_data
-  reported foodborne illness outbreak data.
## Author

Rayna (Nox) Shake- [@NoxRainTempest](https://www.github.com/NoxRainTempest)


## Features

- SQLite databases for efficient querying
- Search recalls by state and recall initiation date range
- Pandas based analysis
- Notebook friendly, reproducible workflow


## Requirements
- Python 3.9+
- Jupyter Notebook
- Required packages listed in requirements.txt

## Notes

- Recall initiation dates are stored in YYYY-mm format as strings.
- Distribution patterns may include multiple states, regions, or nationwide labels.
- This project is exploratory and does not imply causation between recalls and outbreaks.
## Findings

As of my most recent commits, I've found that there does not seem to be much correlation between FDA food recalls and reported foodborne disease outbreaks from the CDC. While I had anticipated more proof of a potential correlation, it also makes sense that there wasn't as the FDA recalls are done in part to limit the spread of foodborne illnesses.
