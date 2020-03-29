# COVID-19-Open-Research-Dataset-Challenge


CORD-19 Initial Notes


* Tasks are evaluated by:
    * Accuracy
        * Did the participant accomplish the task?
        * Did the participant discuss the pros and cons of their approach?
    * Documentation
        * Is the methodology well documented?
        * Is the code easy to read and reuse?
    * Presentation
        * Did the participant communicate their findings in an effective manner?
        * Did the participant make effective use of data visualizations?

* Submission Deadlines
    * Round 1: April 16
    * Round 2: June 16


* Potential Avenues of Approach 
    * Topic Modeling
        * Each task if provided with task details which determine what topics are desired 
        * Convert each “topic” in task details to a topic model THEN find topic matches (using some similarity measure) in the data
    * Clustering/Dimensionality Reduction
        * Autoencoders
        * Pca, t-SNE
        * Reduce the dims of the data into clusters to allow researchers to quickly search the dataset
    * Combine both
        * First cluster articles 
        * Then define topics for each cluster
