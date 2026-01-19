# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.	In two to three sentences, describe the purpose of your survey
2.	Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3.	Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios
1.	You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2.	You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3.	You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1. Sample type
2. Sample size
3. Target population
4. Sampling frame
5. Survey mode(s) 
6. Timeline
7. Response rate
8. Weights
9. Data processing
10. Cleaning, imputation, etc
11. Sources of error
12. Limitations, known biases, etc
13. Link to documentation and any additional sources used


# Your Changes

## Part A - Survey Design: 

The number of your chosen topic: `#`

Describe the purpose of your survey:
```
The main goal of this survey is to find out the real reasons why our junior and entry-level staff are leaving the company so fast. We want to identify specific "pain points" in their daily work life so we can suggest better benefits or management changes to make them stay.
```

Describe your target population, sampling frame, sampling units, and observational units:
```
Target Population: All entry-level and lower-level employees currently working at the tech company.

Sampling Frame: The complete list of active employees in the HR database who are ranked at Grade 1 to Grade 3 (junior levels).

Sampling Units: Individual employees.

Overall Sampling Strategy: I will use Stratified Random Sampling. I will divide the employees by department (e.g., IT, Marketing, Finance) and then randomly pick names from each group. This ensures we hear from all departments, not just the loudest one.
```

Your 5-10 question survey:
```
1. How long have you been with the company, and which department are you in?

2. On a scale of 1 to 10, how happy are you with your current workload?

3. Do you feel that your current salary and benefits are fair compared to other tech companies? (Yes / No / Not Sure)

4. How would you describe your relationship with your immediate supervisor or manager?

5. In the last 3 months, have you actively looked for a job at another company?

6. What is the biggest challenge you face in your role that makes you feel frustrated?

7 If you could change one thing about the office culture to make you stay longer, what would it be?
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
1. Sample Type
The survey used a Stratified Random Sample. The population was divided into different groups (strata) based on geography (provinces) to make sure every part of Canada is represented.

2. Sample Size
The documentation says the field sample was about 50,000 units. From this, they expected to get about 24,000 completed questionnaires. (The actual final number of respondents is usually slightly lower after cleaning).

3. Target Population
All persons 15 years of age and older living in the 10 provinces of Canada. It excludes people living in institutions (like hospitals or prisons) for more than six months.

4. Sampling Frame
The frame was built using a list of telephone numbers (landline and cellular) linked to addresses from the Census and other administrative files.

5. Survey Mode(s)
For the first time in 2018, it used a multi-mode approach:

rGSS (Internet): Respondents could fill it out online.

CATI (Telephone): Interviewers called those who didn't finish online.

6. Timeline
Collection Period: September 4 to December 28, 2018.

Reference Period: The questions asked about activities done in the past 12 months.

7. Response Rate
The overall response rate was 41.9%.


8. Weights
Every respondent has a weighting factor (called WGHT_PER). This tells us how many people in the real population that one respondent represents. They also used "Bootstrap weights" to check for errors in the math (variance estimation).

9. Data Processing
The processing was done using the SSPE system. It involved automated flow edits to fix logic errors, manual and auto-coding for jobs/industries, and record linkage with tax files to get accurate income info. They also created 'derived variables' to help simplify the data for analysis.

10. Cleaning, Imputation, etc.
Cleaning: Used "Flow Edits" to make sure if someone said they "never volunteered," they didn't answer questions about "how many hours they volunteered."

Imputation: They used the "Nearest Neighbour" method (Donor Imputation). If a person left a question blank, the computer found a "similar" person who answered it and copied that answer.

11. Sources of Error
Sampling Error: Because it’s a sample and not a full census, results might vary slightly.

Non-sampling Error: This includes "Coverage Error" (missing people without phones) and "Response Error" (people giving wrong answers by mistake).

12. Limitations, known biases, etc.
Exclusion: People in the Territories (Yukon, NWT, Nunavut) were not included.

Language: Only available in English and French; those who don't speak these might be left out.

Mode Effect: People might answer differently on a computer vs. talking to a human on the phone.

13. Link to Documentation: https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=796234
```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 14 January 2026`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
