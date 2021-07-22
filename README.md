# Gender-Identification-using-Speech

This is a MATLAB application where we take the input speech in realtime and extract information from thet signal.
Using the extracted features we create a score using an emperical formula created by us based on the physiology of human vocal system.
Based on the score of the speech the identified gender is printed along with their score.

The Char_features function helps us to extract the info from the imput signal and return them to main program i.e. the Identification script where the extracted features are evaluated on the emperical formula to return the speech score and the gender of the speaker.
