# NLP Research Project Overview
### Research Question
**When websites are presenting information regarding common vaccinations, what is the typical sentiment towards receiving the vaccine?**

> - Does the sentiment vary from vaccine to vaccine or is it consistent across all?
> - What types of web sources are more likely to hold a positive/negative view towards vaccines?
> - Are government-run websites neutral or partial when presenting vaccine information?
> - Is there any variation in sentiment overtime? Has this effected the vaccination rates?

### Potential Implications
This research could illuminate which vaccines have more public distrust or which are widely accepted. Such information could guide health organizations or governments on the public perception of vaccine mandates or help to guide future interventions to raise vaccination rates. Determining the basis of negative sentiments on such websites will help advise what type of mediation might be successful or what groups should be targeted, whether It based on religion, political affiliation, misinformation, etc.  

### General Process
1.	Web-Scrapping for sites related to vaccinations
2.	Data Cleaning
    - Assign site IDs for all sources
    - Normalize text within each document.= (i.e.. Make all lowercase) – Need to determine if this will this impact sentiment as continuous capitalization could indicate yelling.
    - Tokenize text within each document (Separate into individual words/punctuation)
    - Remove stop words or stem words (Remove words that provide no indication of sentiment such as the/of/and, Group words regardless of tense/ending) – Need to determine if this will impact sentiment as tense can indicate retelling of experiences or distance from subject)
3.	Identify which vaccines are discussed within each document
4.	Utilize measure to quantify or categorize sentiment of each document
5.	Explore the results
    - Determine the sentiment distributions for each vaccine.
    - Investigate the types of websites that generally house negative/positive opinions.
    - Search for common trends among negative documents that indicate a specific group or repeated reasoning.
    - Look specifically at government websites to examine sentiment.

