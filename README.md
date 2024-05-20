# Titanic Dataset EDA

## Steps for README Documentation:
1. Clone the repository.
2. Ensure Python 3.x and required dependencies are installed.
3. Open the EDA file (Prodigy_DS_02.ipynb) in Jupyter Notebook.
4. Run cells to reproduce analysis and visualizations.

## Dataset Type:
- The Titanic dataset includes information about passengers on the Titanic ship, such as survival status, passenger class, name, sex, age, siblings/spouses, parents/children, ticket, fare, cabin, and embarkation port.

## Data Cleaning:
- Initially, the dataset had missing values in 'Age', 'Cabin', and 'Embarked' columns.
- Missing values for 'Age' were imputed using the median age, reducing missing values to 0.
- Missing values for 'Cabin' and 'Embarked' were filled with the most common values.
- No duplicate rows were found in the dataset.

## Visualization and Conclusions:
- **Correlation Matrix Heatmap:**
  - Shows a significant correlation between fare and survival, indicating higher fares increased survival chances.
  ![Correlation matrix heatmap](https://github.com/AnshPandey74/Prodigy_DS_02/raw/f6e8a6a49f6b3d180322a2cd5241e69b6cf6ff3c/screenshots/1.png)
- **Survival Count Plot:**
  - Indicates a survival rate of around 38.4%, with less than half of the passengers surviving.
  ![Survival count](https://github.com/AnshPandey74/Prodigy_DS_02/raw/f6e8a6a49f6b3d180322a2cd5241e69b6cf6ff3c/screenshots/2.png)
- **Passenger Class Distribution Plot:**
  - Reveals that the majority of passengers were in third class, followed by first and second classes.
  ![Passenger class distribution](https://github.com/AnshPandey74/Prodigy_DS_02/raw/f6e8a6a49f6b3d180322a2cd5241e69b6cf6ff3c/screenshots/3.png)
- **Gender Distribution Plot:**
  - Shows more males than females were onboard.
  ![Gender distribution](https://github.com/AnshPandey74/Prodigy_DS_02/raw/f6e8a6a49f6b3d180322a2cd5241e69b6cf6ff3c/screenshots/4.png)
- **Embarkation Point Distribution Plot:**
  - Suggests most passengers embarked from Southampton (S).
  ![Embarkation point distribution](https://github.com/AnshPandey74/Prodigy_DS_02/raw/f6e8a6a49f6b3d180322a2cd5241e69b6cf6ff3c/screenshots/5.png)

These visualizations provide insights into the dataset, highlighting key factors influencing passenger survival on the Titanic.

## Additional Visualizations:
- **Visualization 6**
  ![Visualization 6](https://github.com/AnshPandey74/Prodigy_DS_02/raw/f6e8a6a49f6b3d180322a2cd5241e69b6cf6ff3c/screenshots/6.png)
- **Visualization 7**
  ![Visualization 7](https://github.com/AnshPandey74/Prodigy_DS_02/raw/f6e8a6a49f6b3d180322a2cd5241e69b6cf6ff3c/screenshots/7.png)
- **Visualization 8**
  ![Visualization 8](https://github.com/AnshPandey74/Prodigy_DS_02/raw/f6e8a6a49f6b3d180322a2cd5241e69b6cf6ff3c/screenshots/8.png)
- **Visualization 9**
  ![Visualization 9](https://github.com/AnshPandey74/Prodigy_DS_02/raw/f6e8a6a49f6b3d180322a2cd5241e69b6cf6ff3c/screenshots/9.png)
- **Visualization 10**
  ![Visualization 10](https://github.com/AnshPandey74/Prodigy_DS_02/raw/f6e8a6a49f6b3d180322a2cd5241e69b6cf6ff3c/screenshots/10.png)
- **Visualization 11**
  ![Visualization 11](https://github.com/AnshPandey74/Prodigy_DS_02/raw/f6e8a6a49f6b3d180322a2cd5241e69b6cf6ff3c/screenshots/11.png)
- **Visualization 12**
  ![Visualization 12](https://github.com/AnshPandey74/Prodigy_DS_02/raw/f6e8a6a49f6b3d180322a2cd5241e69b6cf6ff3c/screenshots/12.png)

## Conclusion:
- Survival rate is around 38.4%, showing that less than half of the passengers survived.
- Higher fares correlate with better survival chances.
- Majority of passengers embarked from Southampton (S), and there were more males than females onboard.
- Passenger class significantly impacted survival, with a higher rate among first-class passengers.
