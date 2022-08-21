# Detailed Instructions From Your Instructor Team

The objective of this challenge is for you to gather statistical data about the months of June and December for Oahu and determine how the summer and winter seasons affect the surf and ice cream shop business. Then you'll write a report that describes the key differences in weather between June and December and provide two recommendations for further analysis.

## Deliverable 1: Determine the Summary Statistics for June

For the first deliverable, we are asking you to filter the `Measurement` table in the `hawaii.sqlite` database to retrieve all the temperatures for the month of June as a list, create a DataFrame from the list, and generate the summary statistics from the DataFrame. 

You should not find the tasks in this challenge to be difficult. In this module you have already learned to filter a table using the SQLAlchemy `extract()` function. You have also generated summary statistics in the PyBer module. 

We have provided [starter code](./Resources/SurfsUp_Challenge_starter_code.ipynb) that you should download and add to your surfs_up folder, and rename it `SurfsUp_Challenge.ipynb`. The starter code, has commented steps in the file where you will need to add code to complete this part of the challenge.

## Deliverable 2:  Determine the Summary Statistics for December 

For the second deliverable, you will need to retreive all the temperatures for the month of December as a list, create a DataFrame from the list, and generate the summary statistics from the DataFrame.

The tasks in this challenge are the same as in Deliverable 1. In the [starter code](./Resources/SurfsUp_Challenge_starter_code.ipynb) we have provided steps after Deliverable 1 where you will need to add code to complete this part of the challenge.

## Deliverable 3: A written report for the statistical analysis

Again, the goal of the writing assignment is for you to present your findings in a logical manner. As a reminder, you should use appropriate grammar and structure when writing.

For the written analysis, you should use the repository README.md to write your report. The report will contain three sections: an overview of the analysis, results, and summary.

**Overview of the analysis:** Explain the purpose of this analysis.

**Results:**  Provide a bulleted list with three major points from the two analysis deliverables. Use images as support where needed.

**Summary:** Provide a high-level summary of the results and two additional queries that you would perform to gather more weather data for June and December. 

For June, the highest temperature observed was 85 degrees, and the lowest temperature was 64 degrees. This shows a variance of 21 degrees for June. For December, the highest tempterature observed was 83 degrees, and the lowest tempterature was 56 degrees. This shows a variance of 27 degrees. June temperatures average higher at 74.9 degrees than December at 71 degrees. 

![December_Summary](/December_Summary.png) ![June_Summary](/June_Summary.png)

Some other analysises that could help are the time frame of the lower temperatures and how long they last, the total amount of rain and if the temperature plays a part in that rain, and how many hurricanes affect the area per year.


The README.md document should be in the home directory of your repository. All links should be working, and images and code should be formatted and displayed where appropriate.

## Submission

Make sure you upload the following to your surfs_up GitHub repository:

1. The `SurfsUp_Challenge.ipynb` file.
2. The `hawaii.sqlite` file.
3. An updated README.md that has the written analysis.

## Grading Rubric

The [SursUp Grading Rubric](./Resources/Module_9_Challenge_Grading_Rubric.pdf) is provided for you to use when grading you' submissions.
