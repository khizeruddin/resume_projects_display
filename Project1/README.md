Project Description: Predictive Modeling ML algorithm and Dashboard Development for Scrap Reduction in Tire Production

The project focuses on predictive modeling and dashboard creation to optimize tire production processes by reducing Scrap 56, a specific type of waste categorized under Scrap IV, generated during tire manufacturing. This project uses a combination of historical data analysis, machine learning techniques, and interactive data visualization tools such as Tableau, Power BI, and Excel to deliver actionable insights and improve production efficiency.

Step 1: Understanding the Problem
The initial phase involves defining the scope and objectives of the project. The primary goal is to predict the amount of Scrap 56 generated at the Camacari production plant based on production parameters like Build of Materials (BoM), mold contours, production duration, and tire article IDs. Scrap 56 is a recurring waste type that affects efficiency, cost, and resource utilization.

Step 2: Data Collection and Preparation
Relevant data is gathered from published Tableau data sources, Power BI reports, and Excel sheets. The data includes tire production specifications, historical scrap rates, and plant-specific parameters.

Data Cleaning: Missing values are addressed, and outliers are handled to ensure data integrity.
Normalization and Transformation: Features are scaled and transformed for uniformity, ensuring the neural network can interpret them effectively.
Feature Engineering: Key parameters influencing Scrap 56 are identified and engineered into meaningful inputs for modeling.
Step 3: Exploratory Data Analysis (EDA)
An in-depth analysis of the dataset is conducted to understand the data distribution, identify trends, and uncover relationships between production parameters and scrap generation. Statistical metrics like mean, median, mode, standard deviation, and unique values are calculated for all columns and rows to identify patterns and outliers.

Step 4: Predictive Modeling
A neural network model is developed to predict Scrap 56 based on the cleaned and processed data.

Model Design: The architecture accounts for non-linear relationships between input features and the target variable.
Training and Validation: Historical data from the Camacari plant is used to train the model, and metrics like Mean Squared Error (MSE) and R-squared are calculated to evaluate its performance.
Iteration: Parameters and features are tuned iteratively to improve accuracy and generalization.
Step 5: Dashboard Development
Interactive dashboards are built to visualize key insights and support informed decision-making.

Granularity and Aggregation: Metrics are visualized at various levels of detail (LOD) to offer both high-level overviews and detailed breakdowns.
Discrete and Continuous Data Representation: Appropriate visualization techniques are applied for each data type, such as line charts, bar graphs, and heatmaps.
Interactivity: Tooltips, filters, and drill-down capabilities enable users to explore aggregated and row-level data.
Step 6: Insights and Implementation
The model and dashboards are used to identify production inefficiencies contributing to Scrap 56. Insights guide adjustments in production processes, BoM configurations, and mold specifications. Real-time integration can be explored for ongoing monitoring and dynamic decision-making.

Step 7: Expansion and Benchmarking
Future iterations aim to scale the model to other plants and include additional scrap types for a comprehensive scrap management solution. Benchmarking against other machine learning models (e.g., random forests, gradient boosting) will further refine prediction accuracy and reliability.

Conclusion
This project combines predictive modeling and advanced data visualization to address waste reduction in tire production. By leveraging machine learning and actionable dashboards, it offers a structured approach to optimizing production efficiency, reducing costs, and achieving sustainability goals.
