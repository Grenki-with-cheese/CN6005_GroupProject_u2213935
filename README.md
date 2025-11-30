CN6005_GroupProject_u2213935 (name subject to change)

This is a repository for CN6005 group project. You may refer to Coursework Specifications by following this link to the Coursework2k26.pdf file: https://moodle.uel.ac.uk/pluginfile.php/4774622/mod_resource/content/2/Coursework2k26.pdf

To run the files, you will require Jupyter Notebook. Google Colabs uses the same .ipynb extension, allows us to authorise with Github, work with the same environment across all devices (no missing/depreciated libraries errors) and it is what we were using throughout the semester, so that is what we will be using. Google colabs.

WHAT WE WILL CREATE:
- 3 multiclass image classification models: Logistic Regression(Machine Learning) and Artificial Neural Network using Keras, Convolutional neural Network using Keras (Deep Learning).
- 1 linear regression model.

HOW WE WILL EVALUATE:
The image classification models shall be evaluated using accuracy, confusion matrix and suitable metrics (precision, recall, F-1 score), the model predictions will be interpreted using techniques such as Grad-CAM, LIME or (or) SHAP.

The linear regression model will be evaluated using Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), R-squared (R^2) and visualised with regression line, residual plots, predicted VS actual values. We will apply SHAP for model explainability to interpret feature contributions.

HOW WE WILL STRUCTURE OUR PROJECT/REPOSITORY:
The structure of the project will be such that we will KEEP EACH MODEL on SEPARATE .IPYNB FILE.
For instance:

-   ML_Logisticregression.ipynb
-   ANN_model.ipynb
-   CNN_model.ipynb

-   LR_model.ipynb

-   CN6005_Final.ipynb <---- we will combine all the code here at the very end and submit it.

TO AVOID MERGING CONFLICTS, MAKE SURE TO WORK ON ONE FILE AT A TIME. IF YOU WOULD LIKE TO WORK CONCURRENTLY DO NOT JUST PULL FROM GITHUB.
The EXACT steps to follow in such case would be:

1)   You pull a file from github by going on https://colab.research.google.com/ -> files -> github -> CN6005_GroupProject_u2213935.
2)   Once the .ipynb file is open, press the "share" button.
3)   Type/choose email of your colleague OR copy the link and put send it in the group chat (make sure to properly communicate which file is it).
4)   Your colleague will be able to follow a link sent to their email to view, edit and work on the same file similar to Google Docs.

HOW TO SAVE YOUR PROGRESS:
Once your work is done and all changes are saved on Google Colab, ONE of you will push changes to Github.
The exact steps to do so are as such:

- Press file -> save a copy in github -> choose repository and branch -> add a comment of changes made if you like -> press Ok -> done!

If you EVER worked on Google Docs, it is very similar, and that is also what we are going to use for our report too!
If you have any more questions, please refer to Coursework2k26.PDF file or raise the question on teams at any time.
