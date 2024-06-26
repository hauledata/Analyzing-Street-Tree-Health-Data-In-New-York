
<body>
    <h1>Analyzing Street Tree Health Data in New York</h1>
    <h2>Overview</h2>
    <p>
        This project aims to assess the health status of street trees in New York City through comprehensive analysis of tree species, geographical distribution, and environmental factors. By examining these parameters, the project provides insights into species distribution, key health metrics, and geospatial patterns of tree health across different boroughs of NYC.
    </p>
    <h2>Key Findings</h2>
<ul>
    <li><strong>Large-Scale Data Preprocessing:</strong> Employed Modified Z Score to handle missing data and outliers, ensuring model accuracy.</li>
    <li><strong>Multi-Level Data Analysis:</strong> Utilized Pandas, Numpy, Matplotlib, and Seaborn to explore tree data from city to borough levels.</li>
        <ul>
            <li>Tree Health Assessment: Determined that 95.3% of trees are thriving, with 77.1% in good health and 14.2% in stable condition.</li>
        </ul>
        <ul>
            <li>Problem-Prone Tree Species: Identified Norway Maple, London Planetree, Littleleaf Linden, and Callery Pear as susceptible to root, branch, and trunk issues.</li>
        </ul>
        <ul>
            <li>Barrier Impact Analysis: Found tree barriers significantly reduce health problems, particularly root issues (over 80% reduction).</li>
        </ul>
        <ul>
            <li>Average Tree Diameter by Borough: Noted that Queens has the largest average tree diameter due to its prevalent large-sized species, while Manhattan has the smallest due to its prevalent small-sized species.</li>
        </ul>
    <li><strong>Effective Feature Selection:</strong> Applied Feature Engineering and Principal Component Analysis (PCA) to identify optimal features for three classification models: Logistic Regression, Random Forest, and Decision Tree.</li>
    <li><strong>Skills Demonstrated:</strong> Data Exploration, Data Preprocessing, Feature Selection, Machine Learning, Statistical Analysis, Data Visualization.</li>
</ul>
 <p style="text-align: center;"> 
  <img width="609" alt="Screenshot 2024-06-27 at 01 26 31" src="https://github.com/hauledata/Analyzing-Street-Tree-Health-Data-In-New-York/assets/172208927/7359f93a-9d6c-43f7-8801-6032ebf3038b"> 
 </p> 
<p style="text-align: center;">
<img width="592" alt="Screenshot 2024-06-27 at 01 26 43" src="https://github.com/hauledata/Analyzing-Street-Tree-Health-Data-In-New-York/assets/172208927/74b6bcd1-e2a4-41bc-80a5-a1a54a40d0d2">
</p> 
<p style="text-align: center;"> 
<img width="692" alt="Screenshot 2024-06-27 at 01 26 58" src="https://github.com/hauledata/Analyzing-Street-Tree-Health-Data-In-New-York/assets/172208927/edd53351-dc7c-4c10-8151-807c30bd9995">
</p>
    <h2>Data Sources</h2>
    <p>
        The analysis utilizes street tree census data provided by [source name or organization].
    </p>
    <h2>Files Included</h2>
    <ul>
        <li><strong>analysis.ipynb:</strong> Jupyter notebook containing the code for data analysis.</li>
        <li><strong>data/</strong>: [Directory containing datasets used in the analysis](https://data.cityofnewyork.us/Environment/2015-Street-Tree-Census-Tree-Data/uvpi-gqnh/about_data).</li>
    </ul>
    <h2>Usage</h2>
    <p>
        To replicate the analysis:
    </p>
    <ol>
        <li>Clone this repository to your local machine.</li>
        <li>Ensure you have Python and necessary libraries installed (listed in requirements.txt).</li>
        <li>Open and run the Jupyter notebook <code>analysis.ipynb</code> to view the analysis process and results.</li>
    </ol>
    

<h2>Proposed Solutions</h2>
<ul>
    <li>Implement tree barriers in high-risk areas.</li>
    <li>Enhance regular tree inspections and maintenance.</li>
    <li>Promptly apply pest and disease control measures.</li>
    <li>Raise public awareness about the importance of tree protection.</li>
</ul>

<h2>Future Directions</h2>
<ul>
    <li>Develop predictive models using machine learning to forecast future tree health issues.</li>
    <li>Expand research to include diverse tree species and geographical regions for more comprehensive conclusions.</li>
</ul>
</body>
</html>
