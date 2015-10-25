Check if the dataset exists in the working directory. If not, download it
This is followed by loading hte activities and features information from it
Both the training as well as the test datasets are loaded, only those columns that capture the mean or standard deviation
This is followed up by first loading the activity and subject data for each dataset and then merging them together
Then, the activity and subject columns are converted into factors
The tiny dataset (consisting of the average value of each variable for pair - activity and subject) is created and captured in tiny.txt







