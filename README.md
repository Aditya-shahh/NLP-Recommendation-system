# NLP-Recommendation-system
A robust system which uses content based filtering to accurately recommend users various movies based on the movie which the user has viewed. 

### Guide:

 1. Download the .ipynb notebook file and open it in kaggle kernel
 2. In the kernel, upload the movies dataset.
 3. Then you can run the notebook simply once the dataset is added in the input folder

### Summary:
So, thus I have succesfully been able to develop a recommmender system which basically uses word_to_vec encodings along with tf_idf / CostVectorizer to determine the frequency of words and calculate the matrices 

Further I used cosine_similarity score to evaluate the simalarity of words and then accurately recommend the most 10 similar movies to the user based on the title of the movie which the user gives as an input to the system

### Difficulties faced:
The most difficult part was preprocesing the data. It took me a significant amount of time to understand the data completly, before I could decide what features to include for the recommender system. I had to go through all the columns of the data and had to scrutinize the content, and remove some redundant values as they were becoming an obstacle in merging both the datasets.

Also since the kaggle kernel gives 16GB of RAM so kernel wasnt able to process the complete data. Nevertheless this has always been an issue with the kaggle kernels but still they are quite handy when it comes to performing some quick ML task :)

### Overall I enjoyed working on this task, referred some tutorials which helped me to clarify my doubts and provided me more deeper insight into recommendation systems
