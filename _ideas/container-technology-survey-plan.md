# Container Technologies Survey Plan

## Objectives
Purpose of survey: To assess the community's opinion about container technologies for HPC specifically, and scientific computing generally.

### Main
1. Determine the makeup of the community of people using container technologies for HPC applications (and possibly all scientific applications?)
2. Determine the popularity of different container technologies for HPC applications (and science apps)
3. Assess the opinions about current container technologies for HPC
4. Assess who consumes containers vs. who develops containers vs. who configures container runtimes, registries, and other container technologies

### Optional
5. Assess the opinions about current OCI specification implementations
6. Collect opinions on requested improvements to the OCI specification for HPC containers 

## Population and Sampling

## Population

Our **target population** is all people developing, maintaining, or in any way using container technologies for HPC and/or scientific applications in
any setting.  This includes:
* Research Software Engineers (RSEs)
* Computational Scientists
* Sysadmins (variety of industries)
* Researchers (variety of disciplines)
* Students (variety of disciplines)
* Software Engineers (variety of industries)
* and possibly others

It is important to note that the entire population of folks using container technologies is much broader than the target population because of the
broad use of container technologies in a wide variety of industries, academia, and government applications.  Ultimately we desire our **sample population**
to consist of the larger group of diverse people using container technologies internationally.  Our ultimate target population may contain individuals who
are not aware of OCI.

***Remaining Question:*** Do we intend to focus on results pertaining to HPC?  As in, maybe we collect results from anyone who is willing to fill it out, but we are really concerned with folks using containers for HPC in some way. Said another way: Are we interested in results from folks who have only ever used containers for non-HPC tasks, and thus may have a biased opinion about HPC containers?

## Sampling

### Sampling Method
***Remaining Question:*** Are we planning to use convenience sampling or a form of random sampling?

Convenience sampling is simplest (and thus most common for online surveys) because anyone who lands on the website can take the survey, and the survey can be widely shared unreservedly.  The major downside is that the results cannot reliably generalize about the larger population (relevant to Objectives 1 and 2), and thus limits the statistical methods that can be used to analyze the data [\[1, 2, 3\]](#references).

If we were to select a random sampling method, we could implement it by specifically selecting a wide range of institutions, companies, and/or platforms and randomly select participants to get a sample.  Simple random sampling or cluster sampling might be beneficial to be able to reliably generalize about the population without too much difficulty to implement [\[1, 2\]](#references).

So far, we have only discussed using convenience sampling, but this will significantly limit what we can say about how the data relates to the larger population, what statistical methods we can use, and how we will publish the results.  However, this could be a good method for an initial survey to better understand what research questions there are to ask, if we intend to do multiple surveys.

***Remaining Question:*** What is our sample size?  This is determined by calculating the margin of error based on population size.  However, do we really know the population size?

### Sampling Error
* We should aim for a confidence level of 95% and calculate our margin of error to determing appropriate sample size
* We will need to measure nonresponse error and the numbers of people who do not complete the survey once started
* See the [Decreasing Error](#decreasing-error) section for reducing these types of error

## Data Analysis Plan

The types of statistical methods we can employ to analyze the data are dependent on the sampling method selected.




## Survey Design

### Focus of Questions
The types of container technologies we are interested in asking about include (but are not limited to):
* Container runtimes
* Container registries
* Container orchestration software & tools

Types of applications of container technologies we are interested in asking about include (but are not limited to):
* Cloud computing for science
* Supercomputing
* Machine Learning applications
* Science runs on smaller/institution clusters

### Decreasing Error
To decrease nonresponse error and dropout, we can [\[1, 2\]](#references):
* Minimize the number of questions we ask by encapsulating the objectives well in the phrasing of fewer questions
* Simplify the effort of responding to questions (i.e. do not make people fill out excessive or tedious formats)
* Ask questions based on whether participants do certain tasks (i.e. developers could get different questions than those maintaining their own registries)
* Cater questions towards expertise and knowledge (i.e. don't ask questions about Shifter if they've never used it)
* Allow “decline to answer” or “not applicable” options (also follows good informed consent practices)
* Do not allow multiple responses, or delete multiples from the same respondent

***Remaining Question:*** How will we handle multiple responses (same respondent repeated input)?

### Other Notes
* Include optional demographics collection, especially the respondent's industry and job title
* We can use the website design to implement some of the features desired in the Decreasing Error section, such as hiding questions that do not pertain

## Testing the Survey



## How we will Conduct the Survey

* We will need to submit an application for an IRB expemption/approval - Vanessa has this ready and just needs the final questions
* The survey will be hosted on the [Supercontainers site](https://supercontainers.github.io/) with an about section with something like:

> This survey is being conducted by the [Containers Working Group](https://supercontainers.github.io/containers-wg/) hosted in the [#containers-wg](https://hpc-containers.slack.com/archives/C023C51T8SG) channel of the hpc-containers Slack workspace.  We are a community of researchers interested in containers for High Performance Computing (HPC).  Feel free to [join the Slack](https://join.slack.com/t/hpc-containers/shared_invite/zt-ak9q6jw7-UZgpv7IJua5jCtJ_db_yAQ) and say hello!

* Depending on [Sampling Method](#sampling-method) chosen above, the site will either be open access (convenience sampling) or open based on some kind of access given (random sampling).
* The survey will begin with information on informed consent (necessary)

***Remaining Question:*** Do we have a draft of an informed consent section?

* Respondents will submit responses via our website form, data will be automatically stored for each response, multiple responses should be accounted for, and results will be retrieved after the survey has closed so analysis can begin.

***Remaining Question:*** How long to expect to keep the survey open for?  We will need to keep the survey open long enough to reach the appropriate sample size that meets the desired margin of error to accomplish a 95% confidence interval.

## Remaining Questions
(This section is an aggregation of above listed remaining questions)

* Do we intend to focus on results pertaining to HPC? As in, maybe we collect results from anyone who is willing to fill it out, but we are really concerned with folks using containers for HPC in some way. Said another way: Are we interested in results from folks who have only ever used containers for non-HPC tasks, and thus may have a biased opinion about HPC containers?
* Are we planning to use convenience sampling or a form of random sampling?
* What is our sample size?  This is determined by calculating the margin of error based on population size.  However, do we really know the population size?
* How will we handle multiple responses (same respondent repeated input)?
* Do we have a draft of an informed consent section?
* How long to expect to keep the survey open for?  We will need to keep the survey open long enough to reach the appropriate sample size that meets the desired margin of error to accomplish a 95% confidence interval.


## References

[1] https://study.sagepub.com/sites/default/files/Fricker.pdf

[2] https://www.researchgate.net/publication/275104401_Exploring_ethical_issues_associated_with_using_online_surveys_in_educational_research

[3] https://www.dataquest.io/blog/how-to-conduct-a-survey-and-collect-data-for-a-data-science-project/