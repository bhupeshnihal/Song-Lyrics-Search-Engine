#Song Lyrics Search Engine

This is a domain specific search engine where a user can enter song lyrics and a list of top 10 relevant songs is returned.
The dataset contains musixmatch track id of each song and the corresponding term frequency of each of top 5000 terms that constitute roughly 92% of all lyrics. The dataset is already in bag of words model and hence the same preprocessing technique as implemented in the dataset has been used for user queries as well. Vector space model using TF-IDF scores as corresponding vector components and ISC similarity measure has been used to rank the songs in order of relevance to the user query.

File structure:
music.txt -the dataset of 27143 songs used for training the retrieval system.
words.txt -the track id-song name mappings are stored here.
document vectors.py- Used for creating and storing document vectors with tf-idf scores.
isc_calculation.py-Used for query handling


Link to the dataset: http://millionsongdataset.com/musixmatch/
