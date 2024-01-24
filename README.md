Overview:
This GitHub repository contains the code, analysis, and Tableau visualizations for the NYPD Arrest Data Analysis project. The project aims to provide insights into crime trends, demographics, and environmental factors in New York City using the NYPD Arrest Data from January to June 2023.

Project Highlights:
1. Utilized Tableau, Python, and Apache Spark for comprehensive analysis and visualization of NYPD Arrest Data.
2. Identified top crimes, demographics of perpetrators, and borough-specific variations in law enforcement activity.
3. Implemented predictive models (Logistic Regression, Random Forest) using PySpark for gender and arrest borough, achieving high accuracy.


The attributes is displayed below:

Variable Names - Variable Information
ARREST_KEY - Unique ID for each arrest
ARREST_DATE -	Date of the arrest event
PD_CD	Internal - classification code for the offense
PD_DESC -	Description of the offense corresponding to PD code
KY_CD	- General classification code for the offense
OFNS_DESC -	General description of the offense
LAW_CODE - Charges based on NYS Penal Law, VTL, and local laws
LAW_CAT_CD - Level of offense (felony, misdemeanor, violation)
ARREST_BORO	- Borough where the arrest occurred
ARREST_PRECINCT -	Precinct where the arrest took place
JURISDICTION_CODE -	Jurisdiction responsible for the arrest
AGE_GROUP -	Age category of the perpetrator
PERP_SEX - Sex of the perpetrator
PERP_RACE - Race of the perpetrator
X_COORD_CD - X-coordinate in New York State Plane Coordinate System
Y_COORD_CD - Y-coordinate in New York State Plane Coordinate System
Latitude - Latitude coordinate in WGS 1984
Longitude - Longitude coordinate in WGS 1984
