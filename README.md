# WDM-Ex.NO-10-Sentimental-Analysis-on-Any-dataset-Using-Rapidminer
**DATE:**<br>
**AIM:**<br>
To create a project for Sentimental Analysis on Any Dataset a Using Rapidminer<br>
**Description:**<br>
**Procedure:**<br>
**1.Import Excel data**<br>
a. Drag the "Read Excel" operator from the IO folder onto the process canvas.

b. Double-click on the operator to open its configuration panel.

c. Specify the path to the Excel file you want to analyze.

d. Configure options such as sheet selection, header inclusion, etc.

e. Click on the "Run" button to execute the operator and import the Excel data.<br>

**2.Perform sentiment analysis with Generate Attributes operator**<br>
a. Drag the "Generate Attributes" operator from the Operators panel onto the canvas.

b. Connect the output of the "Extract Sentiment" operator to the input of the "Generate Attributes" operator.

c. Double-click on the "Generate Attributes" operator to configure it.

d. Specify a name for the new sentiment attribute you want to generate (e.g., "Sentiment").

e. Choose the sentiment analysis algorithm, "VADER."

f. Click on the "Run" button to perform sentiment analysis on the Excel data and generate the sentiment attribute.

**3.Interpret and export the results**<br>
a. Analyze the sentiment analysis results from the generated visualizations.

b. If desired, drag the "Write Excel" operator onto the canvas to export the sentiment analysis results to a new Excel file.

c. Connect the output of the visualization operator(s) to the input of the "Write Excel" operator.

d. Configure the file path and other settings for the Excel export.

e. Click on the "Run" button to export the sentiment analysis results to a new Excel file.

**Design:**<br>
<img width="1026" height="545" alt="image" src="https://github.com/user-attachments/assets/60b44cbd-76fb-43a1-b26a-d62b9c799544" />


**Output:**<br>

<img width="1033" height="580" alt="image" src="https://github.com/user-attachments/assets/a551c8a2-f265-4dd8-b61d-d8c6a2020475" />



**Result:**
