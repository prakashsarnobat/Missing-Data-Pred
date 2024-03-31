# Missing-Data-Pred
Predict missing Categorical Data based on other rows with known cells, so that this Dataset is complete, and can be used for further analysis e.g. creating reports in Power BI which display the popularity of Jobs.

# Goals - most important listed first 
1) Deal with missing Data, that is of a discrete nature.
2) Learn Natural Language Processing, with application in Text Classification.
3) Eventually learn how to use ChatGPT to perform the prediction of missing Data, and efficiently clean Datasets in general. 
   
# Step 1 is to find predict the missing cells of the column 'Sector'
Use Sci-kit Learn to perform basic Natural Language Processing of the column 'Job Description', such that the keywords of each cell in the column that arise from this can be used to give a Classification label to the relevant cell. 

# Step 2 is to use the other cells in a particular row to build on Stage 1, and further improve the Prediction of the missing cell.
Exact method used TBC.



# Starting point - 
Work through the following example previously done by somebody else to understand how the NLP method works, and then substitute the dataset and adapt the code to our requirements.

https://dylancastillo.co/text-classification-using-python-and-scikit-learn/   (Provided example)
http://localhost:8888/notebooks/WordClassSKLearn.ipynb  (Link to our own Notebook)
