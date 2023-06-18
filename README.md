# InsightfulTriad
Our team InsightfulTriad contribution to Join the Idea Sprint 2.0 hackathon. 
Our project - Credit Card Fraudulent Prediction.

Credit card fraud has become a pervasive problem in today's digital era, posing significant
challenges to financial institutions and cardholders worldwide. With the rise in online
transactions and the increasing sophistication of fraudulent techniques, it is crucial to develop
robust and intelligent systems to detect and prevent fraudulent activities in real-time. This
introduction sets the stage for addressing the importance of credit card fraud detection and
highlights the need for advanced approaches that can accurately identify fraudulent
transactions, mitigate financial losses, and safeguard the interests of cardholders and financial
institutions.

CREDIT CARD FRAUD DETECTION
----------------------------

DATASET -->

Training.csv: Used to train the JoinTheIdeaSprint2.0_Main.ipynb file
Output.csv: Used to test it using testing.ipynb


MODEL EXECUTION -->

1) Run the JoinTheIdeaSprint2.0_Main.ipynb file present in the Model Building directory.

Note: The python notebooks Splitting the dataset is for model building purpose and may be ignore for direct implementation.

2) Run the testing.ipynb in the Model Building Repository to test it against a custom input (you can use Output.csv in Datasets directory for convenience)

3) Model Deployement :

1. open a code editor like visual studio code 
2. Build the set up configuration of the website like homepage, header etc. 
3. Download the pickle file and create an object of it . 
4. Take input of all the features from the user 
5. Click on submit button to see the prediction.

Steps to run a Streamlit application and predict the output.

1.Change the location of the pickle file path present in the code to the path of your downloaded pickle file.
2.Execute the following command in your command prompt: 
- streamlit run "Your Filename".py 
3. Enter the input features 
4. Click on submit button. Vola!! You can now see if the details are fraudulent or legitimate.
