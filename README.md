# A/B Testing: Light vs. Dark Themes for User Engagement
This project evaluates the impact of Light and Dark themes on user engagement through hypothesis testing using the t-test. The goal is to determine if there are statistically significant differences between the two themes in terms of key metrics like Click-Through Rate, Conversion Rate, Bounce Rate, Scroll Depth, and Session Duration.

## Data Analysis and Methodology
The dataset includes several metrics captured during an A/B test between Light and Dark themes. The metrics analyzed include:

* Click Through Rate (CTR)
* Conversion Rate
* Bounce Rate
* Scroll Depth
* Age
* Session Duration

## Hypothesis Testing with t-test:
For each metric, a two-sample t-test was used to test the null hypothesis that the mean of the metric for both themes is the same. If the p-value is below the threshold 0.05, we reject the null hypothesis, indicating that the difference between the themes is statistically significant.

## Key Findings

* Click-Through Rate: The Dark Theme showed a slight advantage in encouraging clicks, with the t-test confirming a statistically significant difference between the themes (p-value < 0.05).
* Conversion Rate, Bounce Rate, and Scroll Depth: The t-test revealed no statistically significant differences between the themes for these metrics (p-value > 0.05).
* Age and Session Duration: No significant differences were observed in terms of user demographics or session length.

## Technologies Used
* Python: for data analysis and hypothesis testing
    - Libraries: pandas, matplotlib, seaborn, scipy
* Jupyter Notebook: for documenting the analysis and presenting results

