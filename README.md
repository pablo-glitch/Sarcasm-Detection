# Sarcasm-Detection
## A Machine Learning Project on Sarcasm Detection


This is a machine learning project on supervised learning whose objective is no other than... get a sarcasm detector!!!
This is a work in progress!!

The coropora is made up of 3 corpus of comments made found on the web. These corpus are obtained from the Internet Argument Corpus (IAC) 2.0 (Abbott et al., 2016). This is a collection of corpus for research on political debate on Internet forums. It consists of three data sets: 4 forums (414,000 posts), ConvinceMe (65,000 posts), and a sample CreateDebate (3,000 posts). It includes annotations of topics, characterizations of responses (4 forums) and various positions.

It should be noted something important: the documents in each of these corpus have different structural characteristics, as pointed out by Oraby et al. (2016). This means that two corpus, HYP and RQ, seek to capture a specific type of sarcasm each: hyperbole and rhetorical questions, respectively. GEN, on the other hand, captures both hyperbole and critical questions, as well as other types of sarcasm (we could call them "generic") which makes it a heterogeneous set in its composition.

For more information on the corpora please see: Shereen Oraby, Vrindavan Harrison, Lena Reed, Ernesto Hernandez, Ellen Riloff and Marilyn Walker. "Creating and Characterizing a Diverse Corpus of Sarcasm in Dialogue." In The 17th Annual SIGdial Meeting on Discourse and Dialogue (SIGDIAL), Los Angeles, California, USA, 2016. Web: https://nlds.soe.ucsc.edu/sarcasm2


Each **notebook** has a different part of the **project pipeline**:
 1. nb_1_sarcasm_.ipynb: data loading and exploration
 2. nb_2_sarcasm_.ipynb: data preprocessing and feature engineering
 3. nb_3_sarcasm_.ipynb: model training and some partial results
