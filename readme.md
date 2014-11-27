# PBS's Shooting Witness Dataset

Laura Santhanam and Vanessa Dennis of PBS created a dataset of responses by witnesses testifying about Michael Brown's shooting in Ferguson. That dataset was published with [their original article](http://www.pbs.org/newshour/updates/newly-released-witness-testimony-tell-us-michael-brown-shooting/) as [an image](http://newshour-tc.pbs.org/newshour/wp-content/uploads/2014/11/table-finalfinalup4.png). This repo contains a csv dataset based on the values in that image.

- **/data/pbs_data.csv** is the dataset.
- **exploratory_analysis.ipynb** is an iPython notebook containing my exploratory analysis on that dataset.

## Dataset Codebook

- **Variables**:
    - **witness**:
        - String variable. Identifying the witness statement
    - **interview_number:**
        - Integer variable. Denoting the interview number, in cases where a witness was interviewed multiple times.
    - **date:**
        - datetime variable. Denoting the date of the interview.
    - **did MB charge at police car or police officer:**
        - Categorical variable. Coded yes, no, don't know, and NaN based on the witness statement's response to questions. In cases of NaN, it is assumed the witness was not asked that question.
    - **did mb reach into or otherwise directly interacted with police car:**
        - Categorical variable. Coded yes, no, don't know, and NaN based on the witness statement's response to questions. In cases of NaN, it is assumed the witness was not asked that question.
    - **did dw fire gun repeatedly at mb while mb was down:**
        - Categorical variable. Coded yes, no, don't know, and NaN based on the witness statement's response to questions. In cases of NaN, it is assumed the witness was not asked that question.
    - **did mb put his hands at his waist:**
        - Categorical variable. Coded yes, no, don't know, and NaN based on the witness statement's response to questions. In cases of NaN, it is assumed the witness was not asked that question.
    - **did mb face dw when fired upon:**
        - Categorical variable. Coded yes, no, don't know, and NaN based on the witness statement's response to questions. In cases of NaN, it is assumed the witness was not asked that question.
    - **was mb running away from dw when fired upon:**
        - Categorical variable. Coded yes, no, don't know, and NaN based on the witness statement's response to questions. In cases of NaN, it is assumed the witness was not asked that question.
    - **was mb kneeling when fired upon:**
        - Categorical variable. Coded yes, no, don't know, and NaN based on the witness statement's response to questions. In cases of NaN, it is assumed the witness was not asked that question.
    - **did mb put hands up when fired upon:**
        - Categorical variable. Coded yes, no, don't know, and NaN based on the witness statement's response to questions. In cases of NaN, it is assumed the witness was not asked that question.
    - **how many shots were fired:**
        - String variable. Denoting the responses of witness statements.
