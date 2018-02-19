# Missing data

## Aim
- Inform about the existence of missing data
- Show the various forms missing data can take
- Why missing data can be a problem for analysis of data
- How missing data can be tackled

## Topics
- Problem of missing data
- Forms of missing data
- Solution to missing data


## Slides
1. Start with an example
4. Definition of missing data
2. Brief recap about data shape and data types
3. Restate the overall goal: using the most data in the most accurate way
4. Simple example
5. Techniques
4. Example where it went wrong
5. Why important to treat missing data specially (not removing, not causing bias)
6. Solutions (imputation, going back a and ask again)
7. Some practical aspects: encode missingness, clearly state 


## Validation of User Learning
- 
-
-



* Missing data: What looks like a simple string (?NA") can turn an analysis upside down. Support the learner: show possible sources of missing values and methods to tackle them. Explain that we need to think carefully in which of the four categories the missing values, observed in the data, fits in: The missing data (1) is missing at random, (2) carries itself a information, (3) was produced by faulty data extraction, or (4) is correlated to other variables in the data set. The objective is, to build a data set for further analysis that represents the true data as best as possible. Especially (2) and (3) are important to identify, because it means the data needs to be further processed and it might be needed to adjust extracting the data set. (4) Can potentially be imputed by other variables. 
