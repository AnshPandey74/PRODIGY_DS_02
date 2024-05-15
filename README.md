# Titanic Dataset EDA README

## Steps for README Documentation:
1. Clone the repository.
2. Ensure Python 3.x and required dependencies are installed.
3. Open the EDA file (titanic.ipynb) in Jupyter Notebook.
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
- **Survival Count Plot:**
  - Indicates a survival rate of around 38.4%, with less than half of the passengers surviving.
- **Passenger Class Distribution Plot:**
  - Reveals that the majority of passengers were in third class, followed by first and second classes.
- **Gender Distribution Plot:**
  - Shows more males than females were onboard.
- **Embarkation Point Distribution Plot:**
  - Suggests most passengers embarked from Southampton (S).

These visualizations provide insights into the dataset, highlighting key factors influencing passenger survival on the Titanic.

## Conclusion:
- The mean age of passengers is approximately 29.7 years, with a standard deviation of 14.5 years, indicating a wide age range.
- Survival rate is around 38.4%, showing that less than half of the passengers survived.
- Higher fares correlate with better survival chances.
- Majority of passengers embarked from Southampton (S), and there were more males than females onboard.
- Passenger class significantly impacted survival, with a higher rate among first-class passengers.
