# COVID-19-Open-Research-Dataset-Challenge

Eli Laird \
SMU AI Lab \
ejlaird@smu.edu 


This repo contains our efforts to build Natural Language Processing tools to assist researchers around the world with processing ~51,000 research papers related to COVID-19 and similar coronaviruses. All work was done my several undergraduate members of the SMU AI Lab with the guidance of SMU AI Lab faculty. 

Note: This repo is a work in progress. The documentation is still light and unorganized. Please be patient for a final release of our work. 

The dataset used in this repo is provided by the Allen Institute For AI and posted on Kaggle.com. The dataset can be found here: https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge


RESULTS:

#### topics.csv: 
* Description: Every row in this csv contains the words corresponding to each topic
* Link: https://smu.box.com/s/q3jos6b2mqml2mr85zmyhxffx8jz82qu

#### lda_25_model.p
 *  Description: This is the LDA model used to generate the 25 topics in binary form. This can be loaded using the Pickle package in Python
 * Link: https://smu.box.com/s/uqbbw8doy724kpqxjn17x6c5jpdyg59g
 
 #### bhattacharya_similarity_matrix.csv
 * Description: This dataframe contains the bhattacharya distances between every task-document and corpus document 
 * Link: https://smu.box.com/s/eltmk2dphlataps24hol2hilogo265pv
 
 #### metadata.csv
 * Description: Metadata for bjattacharya_similarity_matrix.csv
    * 'Corpus'    : Describes the corpus each document comes from
          * Values: {'main', 'task'}
    * 'Doc_Index' : Index for document in corresponding corpus
    * 'Topic'     : Topic assignment for document 
 * Link: https://smu.box.com/s/tflz9uyoul3yg3jbheynilce3lma5x35
               
                

 
