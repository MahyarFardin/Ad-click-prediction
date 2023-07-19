
# Ad click project with Random Forest and Decision tree

In this project, I tried to predict whether someone with some given information
will click on an advertisement on the internet or not.

## Features of the dataset 
- Daily Time Spent on Site: Daily Time Spent on Site by users
- Age: age of the users
- Area Income: income of the users
- Daily Internet Usage
- Ad Topic Line: the text written on the ad's title
- City: City of the users
- Male: whether they are male or not
- Country: Country of the users
- Timestamp: time of the day they clicked on the Ad
- Clicked on Ad: whether or not they clicked on the add

## Walkthrough

**Step 1**: Loading data and extracting some information from it about attributes


**Step 2**: Preprocessing:

*It is important to mention that a deep analysis of this dataset is available under my data analysis repository*
- taking needed data and transforming them into a usable form (i.e. there might be a relation between daytime and clicking so I separated and saved that info)
- Finding a correlation between attributes using a heatmap (Worthy to mention that data was somehow normalized previously!)
- Normalizing and encoding data

**Step 3**:Appling models:

I skipped models like KNN due to the dataset's sparseness. These models are not suitable for sparse data. 

- Decision tree: This was a good choice because it suits our well with our dataset's characteristics (number of instances and features, etc)
- Random forest: If the decision tree works well, so let's make plenty of them ;)
- Deep neural network: I just tested some simple architectures with some tweaks and saved the best of them.
      
## Feedback

If you have any feedback, please reach out to us at Mahyarfardinfar@gmail.com

## Data
("https://drive.google.com/drive/folders/1Gv0jtk73SVfXBEhjV4sX9WU_hP_w5vA3")
