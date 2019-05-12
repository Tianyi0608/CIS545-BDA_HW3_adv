# CIS545-BDA_HW3_adv
Tf-idf search engine
1. Load the text and clean it use nltk tool kits
2. Generate the vocabulary dictionary: a vocabulary list for all the docs, words frequency in a descending order; lexicon dictionary: word as key, index as value
3. Create doc-term matrix (1D array): a doc-vect matrix, length of matrix is the length of the vocabulary (lexicon), and the value is term frequency (tf): frequency of term/ most frequent
4. Create a list (2D array) contains the doc-term matrix (1D array) for each doc
5. Compute a list of the Inverse Document Frequencies (idf) for each word using the formula: 𝑖𝑑𝑓(𝑤)=log(total number of docs/number of docs containing 𝑤)
6. Scale the doc-term frequency matrix by their idfs
7. Compute cosine similarities between the docs using formula: 𝑠𝑖𝑚(𝑑1,𝑑2)=𝑑1⋅𝑑2/||𝑑1|| ||𝑑2||

First: clean text data and create lexicon dictionary (word dictionary); second: create doc-term matrix using lexicon dict as length(index) and term-frequency (tf) as value for each doc; third: compute the Inverse Document Frequencies (idf) for each word and scale the doc-term matrix by their idfs; forth: compute the cosine similarity between each doc.
