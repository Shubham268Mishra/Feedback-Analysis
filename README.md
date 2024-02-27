# Sentiment Analysis and Complaint Classification
The provided Python script is designed to perform sentiment analysis and complaint classification on customer feedback data. It imports data from multiple sources including Excel and CSV files, cleans the data, and then categorizes feedback into positive and negative sentiments. Additionally, it further classifies complaints into different types based on predefined keywords.

## Requirements
To use the script, you'll need the following dependencies:
```
Python 3.x
pandas
matplotlib
```
You can install the dependencies using the following command:
`pip install -r requirements.txt`

## Usage
1. Clone the repository to your local machine: `git clone https://github.com/Shubham268Mishra/Feedback-Analysis.git`
2. Navigate to the project directory: `cd Feedback-Analysis`
3. Replace the file paths in the script with your own data sources: 
```
# Replace "file_1.xlsx", "file_2.xlsx", and "file_3.csv" with your own file paths
data_1 = pd.read_excel("file_1.xlsx")
data_2 = pd.read_csv("file_2.xlsx")
data_3 = pd.read_csv("file_3.csv", low_memory=False, index_col=0)
```
4. Run the script: `python feedback-sentiment_analysis.ipynb`

## Analysis Results
The script provides several insights into the processed data:

* Distribution of sentiments (positive and negative)
* Relationship between star ratings and sentiments
* Classification of comments into different complaint types
