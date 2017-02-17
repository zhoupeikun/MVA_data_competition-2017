# Data Description

## training_set.csv
for each of the 125 senders ('sender') in the training set, contains a list of message IDs ('mids')

## training_info.csv
each row contains the ID ('mid'), date, body, and recipients of an email from the training set. Make sure you read this file with pandas (as shown in the 'baseline.py' script)


## test_set.csv
for each of the 125 senders ('sender') in the test set, contains a list of message IDs ('mids'). For each of these messages, the recipients are to be predicted

## test_info.csv
each row contains the ID ('mid'), date, and body of an email from the test set. Make sure you read this file with pandas 
(as shown in the 'baseline.py' script)

## predictions_random.txt
the submission file (for Kaggle) of the random baseline.