==================================================
Hate speech dataset from a white supremacist forum
==================================================
 
These files contain text extracted from Stormfront, a white supremacist forum.
A random set of forums posts have been sampled from several subforums and split into sentences.
Those sentences have been manually labelled as containing hate speech or not, according to certain annotation guidelines.
 
More information about the dataset can be found at:
 
O. de Gibert, N. Pérez, A. García-Pablos, M. Cuadros, 2018. Hate Speech Dataset from a White Supremacy Forum. In ALW2: 2nd Workshop on Abusive Language Online.
 
The files/folders are the following:
 
 - all_files: the folder that contains all the forum posts. Each file contains a sentence. The file name is formatted as commentID_sentenceNumber.txt, so the files that share the same number before the underscore pertain to the same comment.
 - sampled_train: a balanced set of files (for "hate" and "noHate" classes) sampled from all_files, used for experiments.
 - sampled_test: a balanced set of files (for "hate" and "noHate" classes) sampled from all_files, used for experiments.
 - annotations_metadata.csv: this file contains the actual label for each file in the previous folders; additionally, it reports how much additional context the annotator required to make a decision over each sentence, the user id, and the subforum id (ids are just numbers that do not further identify people).