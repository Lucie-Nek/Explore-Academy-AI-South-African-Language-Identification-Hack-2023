# Explore-Academy-AI-South-African-Language-Identification-Hack-2023
**Overview**

South Africa is a multicultural society that is characterised by its rich linguistic diversity. Language is an indispensable tool that can be used to deepen democracy and also contribute to the social, cultural, intellectual, economic, and political life of the South African society.

The country is multilingual with 11 official languages, each of which is guaranteed equal status. Most South Africans are multilingual and able to speak at least two or more of the official languages.
From South African Government.

![image](https://github.com/Lucie-Nek/Explore-Academy-AI-South-African-Language-Identification-Hack-2023/assets/114951963/e7081f33-484e-440d-858e-d02fe259cb98)


With such a multilingual population, it is only obvious that our systems and devices also communicate in multi-languages.

In this challenge, you will take text which is in any of South Africa's 11 Official languages and identify which language the text is in. This is an example of NLP's Language Identification, the task of determining the natural language that a piece of text is written in.

**NB**:

The dataset used for this challenge is the NCHLT Text Corpora collected by the South African Department of Arts and Culture & Centre for Text Technology (CTexT, North-West University, South Africa). The training set was improved through additional cleaning done by Praekelt.

The data is in the form Language ID, Text. The text is in various states of cleanliness. Some NLP techniques will be necessary to clean up the data.

**File descriptions**

train_set.csv - the training set
test_set.csv - the test set
sample_submission.csv -> a sample submission file in the correct format

**Language IDs**

afr - Afrikaans
eng - English
nbl - isiNdebele
nso - Sepedi
sot - Sesotho
ssw - siSwati
tsn - Setswana
tso - Xitsonga
ven - Tshivenda
xho - isiXhosa
zul - isiZulu

**Rules for the hackathon**

This is a private hackathon whose primary purpose is for the members of the EXPLORE Data Science Academy to apply what they have learned. If you are part of EDSA contact your mentor for the secret code.

You may use only the datasets provided within this competition. Your solution must use machine learning with an emphasis on classification analysis and related techniques.

Participation within this competition occurs on an individual basis for all students.

Multiple accounts per user are not allowed. Collaboration between individuals is not allowed.

You are not allowed to share your solution code, except where EDSA staff or instructions explicitly request you to do so.

The solution must use publicly available, open-source packages only. Maximum 20 solutions submitted per day.

Your highest-scoring solution will be the one by which you are judged.

**Evaluation**

The evaluation metric for this competition is [Mean F1-Score](https://www.kaggle.com/wiki/MeanFScore). The F1 score, commonly used in information retrieval, measures accuracy using the statistics precision p and recall r. Precision is the ratio of true positives (tp) to all predicted positives (tp + fp). Recall is the ratio of true positives to all actual positives (tp + fn). The F1 score is given by:

The F1 metric weights recall and precision equally, and a good retrieval algorithm will maximize both precision and recall simultaneously. Thus, moderately good performance on both will be favored over extremely good performance on one and poor performance on the other. ## Submission Format
For every index in the dataset, submission files should contain one column: lang_id, the language tag of the predicted language.




