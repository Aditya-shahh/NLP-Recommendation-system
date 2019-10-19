# NLP-Recommendation-system
A robust system which uses content based filtering to accurately recommend users various movies based on the various features like movie genre, rating, cast etc

### Guide:

 1. Download the .ipynb notebook file and open it in kaggle kernel
 2. In the kernel, upload the movies dataset.
 3. Then you can run the notebook simply once the dataset is added in the input folder

### Summary:
Developed a recommmender system which basically uses word_to_vec encodings along with tf_idf / CostVectorizer to determine the frequency of words and calculate the matrices 

Further I used cosine_similarity score to evaluate the simalarity of words and then accurately recommend the most 10 similar movies to the user based on the title of the movie which the user gives as an input to the system


