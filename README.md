### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [Dataset](#dataset)
4. [File Descriptions](#files)
5. [Results](#results)
6. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

For Udacity Capstone project, I chosed the Starbucks challenges to create machine learning model. The data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app.

Questions to be answered:
- Which age groups complete the offer?
- How well can we predict the success of offers?

## Dataset<a name="dataset"></a>

The data is contained in three files:
* portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
* profile.json - demographic data for each customer
* transcript.json - records for transactions, offers received, offers viewed, and offers completed

Here is the schema and explanation of each variable in the files:

**portfolio.json**
* id (string) - offer id
* offer_type (string) - type of offer ie BOGO, discount, informational
* difficulty (int) - minimum required spend to complete an offer
* reward (int) - reward given for completing an offer
* duration (int) - time for offer to be open, in days
* channels (list of strings)

**profile.json**
* age (int) - age of the customer 
* became_member_on (int) - date when customer created an app account
* gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
* id (str) - customer id
* income (float) - customer's income

**transcript.json**
* event (str) - record description (ie transaction, offer received, offer viewed, etc.)
* person (str) - customer id
* time (int) - time in hours since start of test. The data begins at time t=0
* value - (dict of strings) - either an offer id or transaction amount depending on the record


## File Descriptions <a name="files"></a>

- 1 jupyter notebook to showcase work related to the above questions. Markdown cells were used to assist in walking through the thought process for individual steps.  
- data zip file for the above mentioned datasets
- cleaned_data.csv file 

## Results<a name="results"></a>

- The main findings of the code can be found at the post available [here]().

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Udacity and Starbucks for the data. 
 
