# Baani__Sandhu
The objective of this experiment was to build an LLM-based NLP system that processes raw email text and performs summarization, text classification and entity extraction.  
For this we have followed the following process:
1. The txt files are first loaded froma directory into tables (data frames) using pandas library. { We also tested with Spam Email raw text for NLP dataset from Kaggle}
2. There is a single class that includes 4 functions: preprocessing, summarisation, text classification and entity extraction.
3. The preprocessing includes tranforming the string to lower case and removing unnecessary spaces.
4. The other functions include processing by invoking the llm(gemeini flash 2.5 in our case).
