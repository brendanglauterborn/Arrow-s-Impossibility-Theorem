
</head>
<body>
    <h1>The Effect of Total Expenditures per Student on AP Exam Pass Rates</h1>

  <p>
        This project investigates the relationship between per-student expenditures and Advanced Placement (AP) exam pass rates across 1,217 high schools in Texas. 
        By leveraging a dataset rich in educational and demographic details, this study aims to determine how financial resources impact college readiness, 
        as measured by AP exam success.
  </p>

  <h2>Research Motivation</h2>
    <p>
        Education funding is a cornerstone of socioeconomic development. This study evaluates whether increased spending per student correlates with improved 
        AP exam pass rates, with the goal of providing insights into effective resource allocation in secondary education. While initial hypotheses predicted 
        a positive correlation, the findings challenged conventional assumptions, showing a slight negative relationship between funding and AP success.
    </p>
    <h2>Methodology and Data Analysis</h2>
    <ul>
        <li><strong>Dataset Overview:</strong> The analysis uses a cross-sectional dataset provided by Professor Schulman, encompassing financial, demographic, and performance data from Texas high schools.</li>
        <li><strong>Key Variables:</strong>
            <ul>
                <li><strong>Dependent Variable:</strong> AP Exam Pass Rate (<code>pass_rate</code>) – Percentage of students passing AP exams.</li>
                <li><strong>Independent Variable:</strong> Total Expenditures Per Student (<code>total_exp</code>) – Sum of instructional, leadership, guidance, and extracurricular expenditures per student.</li>
                <li><strong>Control Variables:</strong>
                    <ul>
                        <li><strong>Gender Composition (<code>female_share</code>):</strong> Percentage of female students enrolled.</li>
                        <li><strong>Community Type (<code>rural</code>, <code>town</code>, <code>suburb</code>, and <code>city</code>):</strong> Categorical variables indicating the school's geographic context.</li>
                    </ul>
                </li>
            </ul>
        </li>
        <li><strong>Statistical Methods:</strong> Regression analysis was performed to identify correlations and assess the significance of the variables. Multiple regression models were used to account for control variables and isolate effects.</li>
    </ul>

  <h2>Key Findings</h2>
    <ol>
        <li><strong>Expenditures and Pass Rates:</strong>
            <p>Contrary to expectations, higher expenditures per student were associated with slightly lower AP pass rates. This relationship, while statistically significant, showed minimal real-world impact (e.g., a $1,000 increase in per-student spending led to a 0.536% decrease in pass rates).</p>
        </li>
        <li><strong>Community Type:</strong>
            <p>Schools in rural and suburban areas outperformed those in cities, suggesting location-based disparities in educational outcomes. Urban schools face unique challenges that might dilute the effectiveness of increased funding.</p>
        </li>
        <li><strong>Gender Dynamics:</strong>
            <p>Gender composition did not significantly influence AP pass rates, indicating equitable outcomes across genders.</p>
        </li>
        <li><strong>Unaccounted Variables:</strong>
            <p>The study highlights the limitations of excluding factors such as student talent, test-taking skills, and school size. Future research could incorporate these elements to refine conclusions.</p>
        </li>
    </ol>

  <h2>Visual Insights</h2>
    <p>
        The repository includes:
    </p>
    <ul>
        <li>Scatter plots illustrating the relationship between expenditures and pass rates.</li>
        <li>Regression output tables showing the statistical significance of variables.</li>
        <li>Summary statistics and descriptive visuals for exploratory data analysis.</li>
    </ul>

   <h2>Implications</h2>
    <p>
        The findings suggest that increased funding alone does not guarantee higher AP exam pass rates. Policymakers and educators should consider how 
        resources are utilized, focusing on strategies that address specific challenges faced by schools in different contexts.
    </p>

  <h2>Project Structure</h2>
    <ul>
        <li><code>data/</code>: Contains the dataset used for analysis.</li>
        <li><code>notebooks/</code>: Jupyter notebooks with detailed exploratory data analysis and regression modeling.</li>
        <li><code>visualizations/</code>: Charts and graphs generated from the data.</li>
        <li><code>report/</code>: Full research report and citations.</li>
    </ul>

   <h2>Acknowledgments</h2>
    <p>
        This project was conducted as a collaborative effort by 
        <a href="mailto:Jackie166493@tamu.edu">Jaqueline Flores</a> and 
        <a href="mailto:brendangl@tamu.edu">Brendan Lauterborn</a>, 
      with contributions to data analysis, interpretation, and reporting.
   </p>
</body>
