# bikesharing

## Overview of the analysis:
Now that we've gotten a good idea of how to create our story, there is still some more work to be done to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.

For this analysis, you’ll use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:

- Show the length of time that bikes are checked out for all riders and genders
- Show the number of bike trips for all riders and genders for each hour of each day of the week
- Show the number of bike trips for each type of user and gender for each day of the week.
Finally, you’ll add these new visualizations to the two you created in this module for your final presentation and analysis to pitch to investors.

## What You're Creating
This new assignment consists of two technical analysis deliverables and a written report to present your results. You will submit the following:

- Deliverable 1: Change Trip Duration to a Datetime Format
- Deliverable 2: Create Visualizations for the Trip Analysis
- Deliverable 3: Create a Story and Report for the Final Presentation

## Resources
- Software: Git version 2.33.0.windows.2, Visual Studio 1.62.2, Jupiter Notebook, Python, Public TABLEAU (web)

## Deliverables:
1. New Dataframe created with tripduration extra column in the format requested. Additional converted the Gender column in to a readable (Male, Female, Unknown) Data which workls for the user.
The reporisoty has the code used for the convertion of the dataframe using Jupiter Notebook.

2. Visulatizations:
- There is a line graph displaying the number of bikes checked out by duration for all users, and the graph can be filtered by the hour
![Graph1.png](https://github.com/Jcreye75/bikesharing/blob/8e420a8ff0dfc411e6f3e9e033287093349e4d22/Resources/Graph1.png)

- There is a line graph displaying the number of bikes that are checked out by duration for each gender by the hour, and the graph can be filtered by the hour and gender
![Graph2.png](https://github.com/Jcreye75/bikesharing/blob/8e420a8ff0dfc411e6f3e9e033287093349e4d22/Resources/Graph2.png)

- A heatmap is created showing the number of bike trips for each hour of each day of the week
![Graph3.png](https://github.com/Jcreye75/bikesharing/blob/8e420a8ff0dfc411e6f3e9e033287093349e4d22/Resources/Graph3.png)

- A heatmap is created showing the number of bike trips by gender for each hour of each day of the week, and the heatmap can be filtered by gender
![Graph4.png](https://github.com/Jcreye75/bikesharing/blob/8e420a8ff0dfc411e6f3e9e033287093349e4d22/Resources/Graph4.png)

- A heatmap is created showing the number of bike trips for each type of user and gender for each day of the week, and you can only filter by user and gender
![Graph5.png](https://github.com/Jcreye75/bikesharing/blob/8e420a8ff0dfc411e6f3e9e033287093349e4d22/Resources/Graph5.png)

3. Tableau Public Story and visualization.

![TableauChallenge](https://public.tableau.com/app/profile/juan6156/viz/Challenge_Completed/ChallengeStory#1)

Regards

JC