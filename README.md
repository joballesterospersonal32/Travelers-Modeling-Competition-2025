# Travelers-Modeling-Competition-2025
2025 Travelers UMC - Neural Network Machine Learning Model to predict Subrogation opportunities
Description
Overview
You work for TriGuard Insurance Company and going to develop a predictive model to identify potential subrogation opportunities in auto insurance claims using historical claim data from 2020-2021. Subrogation is an important concept in Claim. When our policyholder suffers a loss which is not their fault, the claim professional will pay for the loss and refer to the subrogation professional. The subrogation professional will investigate the loss thoroughly to gather evidence to pursue whoever is that fault and try to recover the money from the responsible third party.

For example, our claimant, say driver A, was backing out of a parking space at the same time as another driver, say driver B. Driver A stopped when he noticed but the driver B continued to back out and impacted our claimant. TriGuard will pay the driver A to fix the car and will seek the reimbursement from driver B who is accountable for the loss.

The goal is to determine which claims have a high likelihood of successful subrogation, understand key indicators, and recommend how TriGuard Insurance can use these insights to optimize recovery processes.

Your goals in this competition are as follows:

• Identify opportunity of subrogation in first-party physical damage claims. • Understand key indicators of subrogation opportunity. • Provide a recommendation on how this information could be leveraged at TriGaurd Insurance Company

Keywords
Claim – request made by a policyholder to the insurance company for payment or compensation for a covered loss or event. First-party physical damage – damages sustained by the insured's own property or vehicle. Subrogation Opportunity – The opportunity that there is a third party to be responsible for the loss.

Modeling
Each group may have at most 5 people and will: a. Work together within groups but not between groups (They can’t provide extra info or help – please contact us directly if anything comes up). b. Build a model to predict subrogation indicator per claim. c. Submit the prediction of the test data as a csv file. (The format requested is provided in the attachment.) d. Prepare a presentation for your business partner to summarize your analysis results. You do not need to explain the problem, just summarize what you did and what you found (see questions to answer in section 'Presentation Instructions' below). e. Each group can make at most 3 submissions per day

Benchmark Model
The score from a simple XGBoost model will be the competition benchmark.

Disclaimer
TriGuard Insurance Company and the data is a fictitious example used for the purpose of this competition only.

Model Evaluation & Competition Logistics
Model Evaluation Metric
Models will be evaluated using F1 score. The submission file should be a CSV containing two columns: claim_number and subrogation (the predicted subrogation opportunity indicator (0 or 1), not the probability).

Competition Logistics
The top teams will be eligible for consideration as the overall campus winner.

The winning campus team will join other winning teams for a virtual job shadow day at the Travelers Hartford campus and make final presentations to a panel who will determine the ultimate winner! The ultimate winner each year going forward will be engraved on a trophy which will be showcased at Travelers for posterity!

Presentation instructions
The finalist teams will be invited to present to the data scientist from Travelers. Here are some examples of questions you may consider including in your presentation.

What methods did you consider (you don’t have to have actually tried all of these methods)?

What method did you choose in the end and why?

How did you do the variable selection? 

What variables help explain the prediction?

What other variables not in the data set do you think might be useful?

How did you test the assumptions of this method?

How did you evaluate your model (e.g. fit statistics, over-fitting, etc.)?

Any concerns about the resulting model?

What questions do you have about the data?

Timeline
10/24 (Tue) - 10:00am EDT	Competition Begins
11/14 (Fri) - 11:59pm EST	Competition Closes
11/17 (Mon) - 10:00am EST	Private Scores Release
11/17 (Mon) to 12/5 (Fri)	Final Presentation Weeks
12/8 (Mon) to 12/12 (Fri)	Winners Announcement
Jan 2026	Final Presentation and Virtual Job Shadow
