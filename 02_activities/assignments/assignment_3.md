# Data Visualization

## Assignment 3: Data Visualization Ethics

### Requirements:
- Let’s return to the data visualizations we evaluated for Assignment 2.  
- For each visualization: 
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) whether or not you think this data visualization is accessible, reproducible, and equitable. 

- Good Visualization
Title: "U.S. Unemployment Rate by Month (2010–2020)"

- Accessibility:
The visualization is highly accessible due to its clean, simple design and clear labeling. It uses appropriate font sizes and avoids over-reliance on color for meaning, which benefits viewers with color vision deficiencies. The color-coded annotations provide context without adding clutter, aligning with Ware’s principles of clarity in Information Visualization. However, adding alt text or descriptions for screen readers would make it fully accessible.

- Reproducibility:
The chart is reproducible if the underlying dataset and methodologies are shared. The use of standard tools like Tableau or Python libraries means users can recreate the graph easily, provided details like time range and event highlights are disclosed. Including a link to the dataset and methods would enhance reproducibility, as Knaflic recommends in Storytelling with Data.

- Equity:
This visualization presents data neutrally, making it equitable in its portrayal of unemployment trends. However, it does not disaggregate data by demographic factors such as race, gender, or socioeconomic status. While this makes it broadly relevant, it misses an opportunity to highlight inequities in unemployment rates. Adding these layers would align with equitable data storytelling practices.

- Bad Visualization
Title: "Favorite Ice Cream Flavors by Age Group"

- Accessibility:
This visualization is not accessible. Overlapping slices, excessive colors, and small, unclear labels make it difficult to read, especially for individuals with visual impairments. The absence of alt text or adaptive design excludes those relying on screen readers. As Few emphasizes in Show Me the Numbers, prioritizing clarity is essential, which this chart fails to achieve.

- Reproducibility:
Reproducing this chart is challenging because it lacks metadata, sample size, or data source information. While pie charts can be created in Excel or Tableau, the absence of a clear methodology or dataset makes this chart’s recreation speculative at best. Including detailed documentation would address these reproducibility issues.

- Equity:
This visualization is inequitable. It aggregates preferences without accounting for diverse demographic or cultural factors that may influence choices. Ignoring such nuances could lead to biased conclusions. Equity could be improved by disaggregating data by factors like ethnicity or socioeconomic status and addressing potential biases in data collection.

      
    - How could this data visualization have been improved (in terms of accessibility, reproducibility, equity)?
 

Title: "Favorite Ice Cream Flavors by Age Group"

- Accessibility Improvements:
The visualization could be made more accessible by addressing its design flaws. Simplifying the chart type (e.g., switching to a grouped or stacked bar chart) would improve readability, as bar charts are easier to interpret than pie charts for comparisons. Larger fonts for labels and data points, along with consistent use of high-contrast colors, would benefit users with visual impairments. Additionally, including alt text or captions for screen readers would ensure the visualization is accessible to all audiences, as recommended by the Web Content Accessibility Guidelines (WCAG).

- Reproducibility Improvements:
Reproducibility requires transparent documentation of data sources, methodology, and assumptions. This visualization lacks such details. To address this, metadata should be included, specifying how data was collected (e.g., survey design, sample size, and demographic representation). Providing access to the raw dataset and step-by-step instructions for recreating the chart in common tools like Excel or Tableau would further enhance reproducibility.

- Equity Improvements:
The visualization fails to consider equitable representation by not addressing potential biases in its data or presentation. Improving equity could involve disaggregating data by additional factors such as gender, ethnicity, or location to highlight differences in preferences among diverse groups. It’s also important to ensure that the sample accurately represents the population to avoid marginalizing specific demographics. Explicitly addressing potential biases in data collection and including contextual notes about the dataset's scope and limitations would further improve equity.

By improving the chart’s design, transparency, and inclusivity, the visualization could better serve its audience and provide actionable insights while adhering to best practices for accessibility, reproducibility, and equity.

- Word count should not exceed (as a maximum) 300 words for each visualization. 

### Why am I doing this assignment?:
- This ongoing assignment ensures active participation in the course, and assesses learning outcomes 2 and 3:  
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:
| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * This markdown file (assignment_3.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
