# Aspect-level-Rating-via-Unsupervised-Federated-Learning

Abstract - 
A novel system based on unsupervised learning in federated setup, which would recommend best product (i.e. mobile phones) to the user for the given aspect, based on the customer reviews that are recorded in different e-commerce platforms (in our case, Flipkart.com and Amazon.in). This methodology can be used as a groundwork, to device solutions that leverage the learning from discrete platforms to allow centralized learning, without compromising data privacy and security.

Methodology - 
1) Data Extraction - Directory Scraping consists of code for scraping of nearly 150 mobile phones' reviews from Flipkart.com and Amazon.in. Python notebooks scrape_flipkart.ipynb and scrape_amazon.ipynb does this job. The scraped data is stored in data_flipkart.csv and data_amazon.csv
2) Preprocessing - Directory Preprocessing contains preprocess_reviews.ipynb that uses uses Natural Language Processing tools to preprocess the text in review comments. Preprocessed data is stored into data_processed_flipkart.csv and data_processed_amazon.csv.
3) CLustering - Actual implementation of Unsupervised Federated Learning:
                analysis.ipynb - Finds Feature Dictionary and creates WordCloud for the same.
                clustering.ipynb - Reads the processed data and performs clustering in federated setup. Various other analyis are shown for better understanding.
                show_data_points.ipynb - To view the clusters formed using MatplotLib.
                
Link to paper: https://www.overleaf.com/read/kynnvfrxvywt
                
                
