# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify:
- 
### Visualization using Python (the file is in participation folder)
> What software did you use to create your data visualization?

Software Used:
- Seaborn and Matplotlib: For creating visualizations.
- Pandas: For data manipulation.
- Requests: For downloading the dataset.
> Who is your intended audience? 
  Intended Audience:
- General Public: Inform about vaccination rates.
- Health Officials and governmental authorities: Insights for public health decisions.
- Health Researchers: Analyze vaccination trends.
> What information or message are you trying to convey with your visualization?

Message Conveyed is to show distribution and percentage of fully vaccinated individuals by age group.

> What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots?

I tried to apply all 3 principles  substantive by  making accurate representation, perceptual by applying  clear labels and distinct colors and aesthetic - making  visually appealing colors and styles. Axes lables, color palette choice, substle gridlines in reading values, markers on the line plot highlight specific data points for better interpretation and using legend that helps in distinguishing data categories.

 > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?

Reproducibility of data visualization is ensured by providing  completed Python code  and  data can be easily downloaded via URL.

> How did you ensure that your data visualization is accessible?

Accessibility - using a clear colorful palette that is easy to read, using clear labels.

> Who are the individuals and communities who might be impacted by your visualization?

General Public, and as a separate categories  Health Officials, Researchers, who can take official desicions and provide awareness campaings.

> How did you choose which features of your chosen dataset to include or exclude from your visualization?

I took as a key informattion age groups and percentage how many people are fully vaccinated. As a separate visualization I decided to compare how many people did one dose, second dose and third dose.  

> What ‘underwater labour’ contributed to your final data visualization product?

- Data acquisition - downloading the dataset using Python’s requests library.
- Data cleaning and preparation -  handling missing values, checking for required columns, and aggregating data by age group.
- Data visualization - creating histograms and pair plots using Matplotlib and Seaborn to ensure clear and accurate representations.
- Aesthetic considerations -  choosing appropriate color palettes, titles, and labels for clarity and readability.
- Reproducibility -  writing clear, documented, and modular code to ensure others can replicate it and visualizate  easily.

### Visualization using Tableau Public (the file is in participation folder)
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    
   
    > How did you ensure that your data visualization is accessible?  
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    

    
    > What ‘underwater labour’ contributed to your final data visualization product?

- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_4.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-4`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
