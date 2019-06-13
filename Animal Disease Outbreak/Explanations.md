# Animal Disease Outbreak

1. Original data is [Kaggle 'Empress Global Animal Disease Surveillance' data](https://www.kaggle.com/tentotheminus9/empres-global-animal-disease-surveillance)
2. Created following extra columns:
   - **'Late Report/Observation'** = day difference between 'observationDate' and 'reportingDate'
   - **'Mortaliy'** = ratio of 'sumAtRisk' cases led to 'sumDeaths'
   - **'Severity'** = ration of 'sumCases' led to 'sumAtRisk'
3. Break down 'SpeciesDescription' column into:
   - **'domestic'** = whether its caused by domestic animal or not (number of domestic species cases)
   - **'wild'** = whether its caused by wild animal or not (number of wild species cases)
   - **all the columns of each 'Species of animals'**
4. Cleaned csv file is uploaded as 'clean_outbreak.csv'
