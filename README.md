# Natural Language Processing for Restaurant Reviews Analysis 

This project was carried out in the Turkish language, hence the variable names and explanations are in Turkish. However, the development methodology is consistent with general computer science logic.

The project developed with Yemeksepeti was presented as a pre-presentation at the school as a graduation project.

The focus of this project is on natural language processing. I used this technique to analyze user reviews for restaurants affiliated with two food delivery services - Yemeksepeti and GetirYemek. The reviews are live data; the data reflects the reviews made by users to the restaurants at that moment.

Data mining and text mining stages include:

1. Cleaning emojis
2. Lowercase-Uppercase conversion
3. Removing unnecessary punctuation marks
4. Tokenization
5. Cleaning of stop words (I created my Turkish dictionary.)
6. Turkish language-specific text mining procedures (linguistic approaches, removal of meaningless suffixes, linguistic origin research and comparison, etc.)
7. Finding unique words and initiating matrix operations
8. Creating frequency matrices
9. Creating the distinctness matrix
10. Scaling the distinctness matrix data in logarithm base.

After these processes, unsupervised learning algorithms have been used. The machine learning algorithms used are implemented without using ready-made libraries in python. These stages are:

1. Application of the KMeans algorithm
2. Optimization of K (with the Elbow method)
3. KMeans result geometric distance matrix
4. Calculation of silhouette and Dunn score
5. Summaries based on distances
6. Printing and checking the inferences.

This project is a valuable example of software with a computational complexity of n^3 and has substantial utility.

