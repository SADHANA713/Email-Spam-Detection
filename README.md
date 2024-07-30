# Email-Spam-Detection
# Project Overview
Email spam detection is a vital process in managing email communications. Spam emails are unsolicited messages, often sent in bulk, that can clutter inboxes and sometimes pose security risks. The goal of this project is to develop a machine learning model to accurately classify emails as either spam or ham (non-spam).

# Exploratory of data analysis for email spam detection
Data Overview:Loaded the dataset and displayed the first few rows to understand the structure and content.Checked the column names and the types of data in each column.

Checking for Data Types:Verified that the Category column is categorical, representing spam or ham.Confirmed the Message column is textual data, containing the content of the emails.

Finding Missing Values:Ensured dataset completeness using isna().sum() method to confirm no missing values in either Category or Message columns.

Removing Duplicates:Detected and removed 415 duplicate rows using data.drop_duplicates(), ensuring unique email messages for analysis.

Class Distribution:Visualized the distribution of spam and ham emails using a bar plot to understand the balance of the dataset.

Text Length Analysis:Calculated the length of each email message and visualized the distribution using histograms. Compared the distributions for spam and ham emails to identify any noticeable differences.

Word Frequency Analysis:Utilized the CountVectorizer to determine the most common words in spam and ham emails.Visualized the top 20 most frequent words in each category using bar plots

# Dataset Description for Email Spam Detection Project
The dataset comprises 5,572 rows and 2 columns. The two columns are Category, which indicates whether an email is spam or ham, and Message, which contains the email text. The dataset is imbalanced, with 4,827 instances labeled as ham and 747 instances labeled as spam.
