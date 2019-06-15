# Animal Disease Outbreak

1. Original data is [Kaggle 'Empress Global Animal Disease Surveillance' data](https://www.kaggle.com/tentotheminus9/empres-global-animal-disease-surveillance)
2. Created following extra columns:
   - **'Late Report/Observation'** = day difference between 'observationDate' and 'reportingDate'
   - **'Mortaliy'** = ratio of 'sumCases' led to 'sumDeaths' (unit: %)
   - **'Severity'** = ratio of 'sumAtRisk' led to 'sumCases' (unit: %)
3. Break down 'SpeciesDescription' column into:
   - **'domestic'** = whether its caused by domestic animal or not (number of domestic species cases)
   - **'wild'** = whether its caused by wild animal or not (number of wild species cases)
   - **'unspecified'** = whether species is unspecified or not (not sure whether its from wild or domestic, or kind of species)
   - **'species'** = list of name of species
   - **all the columns of each 'Species of animals'**
4. Cleaned csv file is uploaded as ['clean_outbreak.csv'](https://github.com/JessJihyunLee/Tableau-Data-Preprocessing/blob/master/Animal%20Disease%20Outbreak/clean_outbreak.csv)
