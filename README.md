# EDA — Titanic Dataset

Exploratory data analysis of the Titanic passenger dataset (**891 passengers × 12 features**), focused on one question: **who survived, and what actually separated them from those who didn't?**

## What the notebook explores

- **Data quality** — dimensions, dtypes, missing values, summary statistics, correlation and outlier checks
- **Overall outcome** — how many passengers survived vs. died
- **Class** — passenger distribution and survival rate across 1st / 2nd / 3rd class
- **Gender** — survival rate by sex, and age–gender distributions
- **Age** — average age and survival patterns across age groups
- **Embarkation port** — passenger distribution and survival rate by port (Cherbourg, Queenstown, Southampton)
- **Family aboard** — survival rate by number of siblings/spouses (`SibSp`), parents/children (`Parch`), and the two combined
- **Fare** — fare distribution, and average fare paid by survivors vs. non-survivors

The consistent story the data tells: survival was strongly patterned by **class, gender and fare** — the notebook quantifies each effect rather than just plotting it.

## Dataset

The classic Titanic dataset: passenger class, name, sex, age, family counts, ticket, fare, cabin and embarkation port, with the binary `Survived` outcome.

## Tools

Python · pandas · NumPy · Matplotlib · Seaborn

## Run it

```bash
jupyter notebook EDA_Titanic_dataset.ipynb
```

## Author

**Muhammad Hamza** — Data Scientist · [GitHub @mhamza6051](https://github.com/mhamza6051)
