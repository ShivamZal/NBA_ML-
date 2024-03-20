<h1>Forecasting Home Team Wins or Losses Using ML Algorithms</h1>

<p>This project focuses on utilizing machine learning algorithms to forecast whether the home team will win or lose in NBA games. The dataset spans from 2003 to 2022, comprising over 25,000 rows with final scores of all games. Key attributes include home points, away points, field goal percentage (FG%), three-point percentage (3pt %), advanced stats, and defensive stats.</p>

<h2>Algorithms and Libraries</h2>

<p>The project implements three machine learning algorithms: Random Forests, K-Nearest Neighbors (KNN), and Logistic Regression. Among these, Random Forests and KNN are classification algorithms, while Logistic Regression serves as a regression algorithm. Libraries such as Pandas, Scikit-learn (sklearn), Seaborn, NumPy, and MLxtend are utilized for data manipulation, visualization, and machine learning tasks.</p>

<h2>Project Question</h2>

<p>The central question driving the project is: Can past data predict whether the home team will win? The project is structured into three main files:</p>

<ol>
  <li><strong>Data Cleaning and EDA:</strong> This phase involves the removal of missing values, conversion of relevant columns to datetime and numerical types, and exploratory data analysis (EDA). Figures include comparisons of total points scored by year, wins by year, and line plots of home and away team FG% and 3pt%.</li>
 <p></p>
  <p>1. Wins for home and away teams from 2003-2022</p>
<p align="center">
  <img src="https://github.com/ShivamZal/NBA_ML-/blob/main/viz1.PNG" alt="GitHub Logo" width="80%" height="60%">
</p>
<p>1. Points scored for home and away teams from 2003-2022</p>
<p>
<p align="center">
  <img src="https://github.com/ShivamZal/NBA_ML-/blob/main/viz2.PNG" alt="GitHub Logo" width="80%" height="60%">
</p>
<p></p>
<p>3. Line plot showing that home teams have relatively higher percentage than away teams
<p align="center">
  <img src="https://github.com/ShivamZal/NBA_ML-/blob/main/viz3.PNG" alt="GitHub Logo" width="80%" height="60%">
</p>
  <li><strong>Merge:</strong> In this step, the two files are merged to incorporate additional information such as city names, average capacity, and team names into the dataset. Variable selection is also performed here.</li>
  <li><strong>ML:</strong> This phase begins with splitting the data into training and testing sets (50-50 split). Selected variables include points scored by home and away teams, FG% from free throw, 3pt %, 2pt %, and various statistics like efficiency percentage, fouls, rebounds, steals, blocks, and assists. The target variable is binary, indicating whether the home team wins (1 for yes, 0 for no). Confusion matrices for Random Forests, KNN, and Logistic Regression are presented, with Logistic Regression performing the best due to its suitability for binary classification.</li>
</ol>

<p>4. Confusion matric for Random Forest with Accuracy </p>
<p align="center">
  <img src="https://github.com/ShivamZal/NBA_ML-/blob/main/CM.PNG" alt="GitHub Logo" width="80%" height="60%">
</p>
<p></p>
<p>5. Confusion Matrix for Logistic Regression with Accuracy
<p align="center">
  <img src="https://github.com/ShivamZal/NBA_ML-/blob/main/viz4.PNG" alt="GitHub Logo" width="80%" height="60%">
</p>
<p></p>
<p>6. Confusion Matrix for KNN with Accuracy
<p align="center">
  <img src="https://github.com/ShivamZal/NBA_ML-/blob/main/viz5.PNG" alt="GitHub Logo" width="80%" height="60%">
</p>

</ol>

<h2>Future Scope</h2>

<p>There is ample opportunity for future enhancements, such as experimenting with different search parameters and incorporating advanced NBA statistics like effective field goal percentage (eFG%), true shooting percentage (TS%), player combinations, and more complex metrics. These advancements can further refine the predictive capabilities of the model and contribute to improved decision-making within NBA organizations.</p>
