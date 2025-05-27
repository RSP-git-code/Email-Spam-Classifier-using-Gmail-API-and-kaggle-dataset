# Email Spam Classifier

A machine learning project to classify emails as **spam** or **ham** using real-time Gmail data and a labeled Kaggle dataset.

## Features

- Gmail API integration to fetch real emails
- Text preprocessing (cleaning and normalization)
- TF-IDF vectorization
- Logistic Regression model
- Threshold-based spam classification
- Test case predictions with probability scores

##  Setup

1. Enable Gmail API and download `credentials.json` from Google Cloud Console.
2. After Enabling finish OAuth 2.0 configuration where you have to give details about your project
3. Once the Oauth configuration is done you will get a credentials.json file
4. Download that file  and place it in same directory or provide the file path
5. Next step , Provide test subjects from which you are acessing the email cause gmail wont let you access just anyone email so for that give your email in test subject option and it will permit to  access your emails .Otherwise it will not permit and authentication section fails
6. Run the script to authenticate and fetch emails.
7. Place `mail_data.csv` (Kaggle dataset) in the same directory.
8. 
##  Requirements
1 Use jupyter notebook or tensorflow for faster processing
2. Download required libraries :
   . Numpy: pip install Numpy
   .scikit-learn: pip install scikit-learn
   . Pandas:pip install pandas
   .Google Api :pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib
3. Enabled Gmail API with credentials.json file and test subjects email ids

   


