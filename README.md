# Garage Crafters Renovation and Targeted Construction
Garage Crafters Inc., headquartered in Ames, Indiana, is a leading design firm specializing in personalized garage renovation and construction services. The company's mission is to offer tailored garage improvement recommendations to homeowners in Ames, Indiana, aiming to enhance property value. Additionally, Garage Crafters aims to identify specific neighborhoods in Ames that are most likely to require garage construction or renovation services.

## Data Dictionary

| Feature        | Type    | Description                                           |
|----------------|---------|-------------------------------------------------------|
| GarageArea     | Integer | Size of garage in square feet.                        |
| GarageCars     | Integer | Size of garage in car capacity.                       |
| GarageCond     | String  | Garage condition.                                     |
| GarageFinish   | String  | Interior finish of the garage.                        |
| GarageQual     | String  | Garage quality.                                       |
| GarageType     | String  | Garage location.                                      |
| GarageYrBlt    | Float   | Year garage was built.                                |
| GrLivArea      | Integer | Above grade (ground) living area square feet.         |
| Neighborhood   | String  | Physical locations within Ames city limits.           |
| SalePrice      | Integer | The property's sale price in dollars (target variable).|

## Executive Summary
Garage Crafters Inc. embarked on a mission to provide expert garage renovation and construction services to homeowners in Ames, Indiana. The primary objectives of this project were to:

- Build a predictive model that suggested beneficial garage renovations based on the garage's intended use.
- Evaluate the impact of different types of garage renovations on the estimated property value.
- Calculate the potential return on investment (ROI) for common garage renovation projects in Ames, Indiana.
- Identify neighborhoods or property types in Ames that are most likely to require garage construction or renovation services.

To accomplish these goals, data related to garage conditions, intended use, neighborhoods, garage size, and garage finishes were analyzed. Machine learning techniques were employed to develop predictive models and uncover valuable insights.

The project provided Garage Crafters with data-driven recommendations for garage improvements, enabling homeowners to increase property value. Furthermore, the identification of neighborhoods or property types in need of garage renovation services guided Garage Crafters' targeted marketing and resource allocation.

## Data Cleaning and EDA (Exploratory Data Analysis)
Data was cleaned to handle missing values, outliers, and any necessary feature engineering. Exploratory data analysis involved assessing the distributions, correlations, and relationships between garage-related features and property values.

### Preprocessing and Modeling
Categorical variables were one-hot encoded. Data was split into training and testing sets for modeling. Scaling was applied to features as needed. Feature selection techniques were employed to improve model performance. Linear regression, among other models, were used to predict each coeffiecient's affect on sale price of the home.

### Evaluation and Interpretation
Model performance was evaluated using relevant metrics. The baseline score was established and compared to model results. The model's interpretability and insights into the factors affecting property values were discussed.

### Business Recommendations
Garage Crafters Inc. aimed to provide actionable recommendations for homeowners in Ames, Indiana, while efficiently targeting neighborhoods or property types that required their services. The project's findings were instrumental in making strategic decisions for the company's marketing efforts and resource allocation.

Based on the analysis, Garage Crafters could:

- Suggest garage renovations tailored to the garage's condition and intended use.
- Assess how different types of garage renovations impact property values.
- Calculate the ROI for common garage renovation projects.
- Identify high-potential neighborhoods or property types in need of garage construction or renovation services.

The insights gained from this project empowered Garage Crafters to offer personalized garage improvement recommendations and enhance property values for homeowners in Ames, Indiana.


