# The Sound of Reconstruction: The Repertoire of the Antwerp Opera after the Second World War (1946-1963)
This repository contains the notebooks and data used in “The Sound of Reconstruction: The Repertoire of the Antwerp Opera after the Second World War” by Amber Truyts, submitted for the Master in Digital Text Analysis at the University of Antwerp (2024–2025).

Notebooks:

- 1_preprocessing -> Notebook containing the preprocessing of the dataset collected by me (1946-1963) and the merging of previous datasets by Mona Allaert (1893-1934) and Elisabeth Jansen (1933-1946)
- 2_data_exploration -> Notebook exploring popular productions and composers in complete_dataset, with focus on German productions and Wagner
- 3_language_distribution -> Notebook exploring the distribution of languages in performances in complete_dataset
- 4_comparison_WWII -> Notebook containing a comparison of productions and performances, with focus on 5 years before, during, and after WWII (1935-1950)
- 5_leaflet_language -> Notebook analyzing the leaflet langauge of my dataset (1946-1963)
- 6_themes -> Notebook exploring the themes of popular productions after WWII (1946-1963)
- 7_GLM_prep -> Notebook containing the preprocessing of the complete dataset (1893-1963) for the Generalized Linear Model
- 8_GLM -> Notebook containing the Generalized Linear Model of the complete dataset (1893-1963)
- tesseract_OCR -> Notebook provided by Sara Budts containing the script to run Tesseract on scans from my dataset

Materials:

- dataset.csv -> csv file with data collected by me (1946-1963)
- cleaned_dataset.csv -> csv file with data collected by me (1946-1963) after preprocessing
- Merged_Dataset.csv -> csv file with data collected by Mona Allaert (1893-1934) and Elisabeth Jansen (1933-1946), merged by Jansen
- complete_dataset.csv -> csv file with all data collected by Allaert, Jansen and me (1893-1963)
- META3.txt -> txt file containing metadata (composer, original language, original title, etc.) which was added during the preprocessing
- scans -> folder containing the original scans used for theme analysis
- theme -> folder containing txt files containing the text from the scans used for theme analysis
