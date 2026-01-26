# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad): 

- Bad: https://public.tableau.com/app/profile/rush1056/viz/Temperatureanomalydifference-Australia/Dashboard2
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      I think that this visualization has some good points, but tries to present too much data overlapping eachother, making it difficult to parse.
      
      In terms of Provenance rhetoric, this visualization provides a link to the Government of Australia, Bureau of meteorology's website outlineing how data used in the graph is collected [1]. This website details that the temperature anomaly value releative to the mean temperature between 1961 and 1990 is an established convention for measuring temperature changes, and that measurements were taken across a fairly evenly distributed set of stations across Australia. The website also provides a peer reviewed analysis on the data collection methods, lending further credibility to this visualization. 
      
      In terms of Perceptual retoric, the main message is that temperature anomaly seems to grow over years, with more recent years having very high anomaly scores. This message can only be determined by fully watching the video, since, at a glance, we cannot tell which year is associated with which temperature anomally. The choice of a divergent colourbar helps their message since for this temperature anomaly value since a reader can tell at a glance whether a temperature anomaly is possitive or negative. The animation also shows the temperature anomally getting further from the center of the plot, i.e., more possitive as time goes on, showing that average temperature is increasing.
      
      This type of radial line plot is rare, since unlike months of the year, not a lot of other variables that we commonly plot are cyclical. The user must hover over each datapoint to get its temperature value. This adds cognitive load, as the extra work of hovering over points to read their value makes the graph more time-consuming to interact with.
      
      ```
    - How could this data visualization have been improved?  
      ```
      The main disadvantage of this plot is its inclusion of extranious detail and high cognitive load. All years are plotted overlapping with eachother as we move forward in time, so it is difficult to visualize changes between the temperature anomally in late years than in earlier ones. I would argue that these later years are more releavant to our analysis of climate change since there are more influenced by modern policies. I would add an option to set a range of years to show, rather than show every year's data overlapping eachother. Otherwise, it we want to show many years at once, maybe grey out the previous years, and only have colour for the current year?
      
      To make this graph easier to read, I would include numbers along the circular grid lines denoting temperature and maybe highlight the circle denoting a temperature anomaly of 0C.
      ```
      
- Good: https://public.tableau.com/app/profile/neil.richards/viz/globaltemperatures/Dashboard1
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      I think this visualization is easier to read at a glance, making it a more effective at converying its message. However, it does lack some details when it comes to reproducibility.
      
      In terms of provenance rhetoric, this visualization is harder to reproduce. The plot includes a small note to 'www.usatoday.com' it its upper corner as the source of its data. When I went to their weather data catalogue, I could not easiely find a global median temperature data survey, only one for the US. This link may be referencing an article referenced in USA today, but it is difficult to pinpoint the source of this data just from this link. With only this information, readers cannot easiely find out the significance of the 1961-1990 time period or figure out if this data is preferentially collected from certain locations on earth.
      
      The message of this graph is much easier to tell from a glance. This graph also aims to show that the median temperature is increasing from the reference to the mean temperture of the 1961-1990 time period. The divergent colourbar centered on 0 clearly lets the reader clearly tell that temperature anomally increases as years progress as we move down the colourmesh plot on the left or bar plots on the right. The choice of haivng red be warmer also takes advantage of Germain cognitive load since readers would typically associate red with warm. The median, maximum, and minimum plots on the right can also be helpful in that they let the reader quickly see that this trend in increasing temperatures affects not only median temperature, but also temperature extremes. However, this is a new piece of information that is added, and could increase cognitive load.
      ```
    - How could this data visualization have been improved?  
      ```
      Overall, this plot satisfies 3 of the 4 conventions of data visualization. The main area of improvement is citing where it got its data from in more detail. This will allow readers to check if this data comes from a reputable source, determine whether there were any biases in data collection (i.e., more climate surveying stations in norther hemisphere), and read about the significance of choosing median difference between a given year and the referecne 1961-1990 average.
      
      Additionally, to help limit visual clutter, I would include the mean in a range of 10 years instead of plotting each year as its own line for the colourmesh section of this plot. This will reduce the visual clutter of having so many small lines that tell mostly the same information. I would keep this finer data spacing for the bar graphs, since they provide more detail on years like 1880, which do not follow the general trend of higher temperature anomaly in more recent years.

      ```      
      - Citations:
      '''
      [1] About the temperature timeseries graphs. Temperature timeseries graphs. (2025). https://reg.bom.gov.au/climate/change/about/temp_timeseries.shtml 
      '''
- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
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
* Submission Due Date: `23:59 - 10/26/2025`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
