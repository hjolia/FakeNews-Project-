# FakeNews-Project-

This is a fake news predictor project, trained on the Fake News Corpus dataset. The program cleans the data, to then be fed into a Simple model based off logisitic regression and an Advanced model based off neural networks. 

Preferably run the program with python 3.11.7.
The following packages need to be installed in the environment:
- clean_text
- numpy
- pandas
- matplotlib
- nltk
- scikit-learn
- tensorflow
- gensim

'news_sample.csv' refers to a sample of the Fake News Corpus. 
'reliable_scraped_data.csv' refers to a file consisting of scraped content from the BBC, which has gone through the same preprocessing as the FNC dataset.
'test.tsv' is a file from the LIAR dataset. 
'cleaned_dataset_big.csv' is the '995,000_rows.csv' file after has going through cleaning. Run the cleantext_clean, remove_stopwords and stem_input functions on the dataset (995,000_rows.csv) to produce this file. 

To run the programs, ensure all files used in the program are saved in the same folder as the program. 
