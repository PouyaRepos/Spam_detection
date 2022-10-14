# Spam_detection

This project is part of the exam Intelligent Data Analysis. The goal is to train an email 
spam filter which should mark the incoming emails of all employees as spam or non-spam.
The emails are parsed by a module and converted into the bag-of-words representation.
A total of 57,173 different words (features) are distinguished. The aim of the filter
is to identify a maximum number of spam emails, with a maximum of 0.2% of all
legitimate emails being classified incorrectly. In addition, the company wants
to make a statement about the effectiveness of the filter on future emails, i.e., what
percentage of incoming spam emails will be identified in the future.
NOTE: For the sake of showing the procedure and in order to shortening the
computation time, only a small slice of data, namely (200, 400) out of (10000, 57173) will be used.
Therefore, the accuracy is showing the trained model's result on that small portion of data.
