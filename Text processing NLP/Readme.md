# the first task I made in up work 
# NLP project requirment 


Need the fully executed ipynb file (preferably written on google collab) written for the given dataset. Need it within the next 8 hours. The quicker it is delivered the better.
You have to do the following tasks:

1. Combine TI and AB to form a single "Text" column.

2. Preprocess the text column - normalize, remove stopwords, punctuation and numbers, and lemmatize. If you can, get bigrams as well.

3. For each company, create a text file that concatenates the patent titles and abstracts (i.e., the text column). This step will give you 27 files (as there 27 companies in the dataset).

4. Use the 27 files to create a hierarchical cluster of the companies. Also, create a MDS map of the companies.

5. Perform topic modeling using LDA and NMF on the "Text" column (not on the 27 files). Assume that there are 40 topics in the corpus.

6. LDA will give you a document-topic matrix that shows the probability distribution of each document (i.e., patent) across the topics). Note that there will be many patents from a company. You need to find the average of the probabilities for each of the topics for each company. This will give you 27 rows, one for each company. The row will contain the average probability for each topic. Perform a hierarchical cluster of this data to see the similarity between companies based on topics.

Summary of required output:

a. 40 topics using NMF and LDA

b. Hierarchical cluster of companies based on text similarity of patents

c. MDS map of the companies using text similarity
