In this project, we will do NLP Analysis on 10-k financial statements to generate an alpha factor. For the dataset, we'll be using the end of day from Quotemedia and Loughran-McDonald sentiment word lists.

We will follow following steps:-
1. Download 10-K Documents from SEC.GOV
2. Parse the 10-K Data.
3. Clean the dataset using Regular Expressions for <Type> Tags.
5. Remove the Stop Words.
4. Stemming and Lemmatization.
5. Analysis using Loughran McDonald Sentiment.
Loughran and McDonald sentiment word lists. These word lists cover the following sentiment:
i) Negative
ii) Positive
iii) Uncertainty
iv) Litigious
v) Constraining
vi) Superfluous
vii) Modal
6. Jaccard Similarity
7. Generate TFIDF from 10k
8. Cosine Similarity
9. Evaluate Alpha Factors.
