# TFIDF

### Term Frequency
How many times does a particular word appear in a document?

### Inverse Document Frequency
How many times does that word appear in all documents?

tf(d, t): Number of times word t appears in document d  
df(t): Number of documents in which the word t appears  
idf(t): A number inversely proportional to df(t)  
#### $$idf(t) = log(\frac{n}{1 + df(t)})$$

#### Features
- Fast speed, simple calculation
- No reflection of sentence structure and order
- No DL required
