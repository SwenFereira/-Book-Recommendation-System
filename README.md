# -Book-Recommendation-System

In this Capstone Project , The main objective is to create a book recommendation system for users. 

Recommender systems are machine learning systems that help users discover new product and services. A book recommendation system is a type of recommendation system where we have to recommend similar books to the reader based on his/her interest.

The Book-Crossing dataset comprises 3 files.

1. Users:
 
● Data set Contains ‘User-ID’ , ‘Location’, ‘Age’ information’s. 
● The Data set Contains 278858 Rows
 
2. Ratings:

● Data set Contains ‘User-ID’ , ‘ISBN’, ‘Book-Ratings’ information’s. 
● The Data set Contains 1149780 Rows

3. Books:

● Data set Contains 'ISBN', 'Book-Title', 'Book-Author', 'Year-Of-Publication', 'Publisher', 'Image-URL-S', 'Image-URL-M', 'Image-URL-L‘ information’s. 
● The Data set Contains 271354 Rows.

The project is executed in 5 main steps:

1.	Data Overview 
2.	Data Preparation	
3.	Exploratory Data Analysis 
4.	Model Creation 	
5.	Evaluation


Exploratory data analysis (EDA) was performed to gain better understanding about the data . Some understanding from the data was received such as, We have 8061 unique Book Title & The top most book title found is Wild Animus. We have 4249 unique Authors & The top most author found is Nora Roberts. We have 1075 unique Publishers & The top most Publisher found is Pocket. Most books were published in the year of 2002.

Models experimented with:

1.	k-Nearest Neighbors (kNN)
2.	Singular Value Decomposition (SVD):


Conclusion: 

● A recommendation system helps an organization to create loyal customers .

● The recommendation system today are very powerful that they can handle the new customer too who has visited the site for the first time. 

● They recommend the products which are currently trending or highly rated and   they can also recommend the products which bring maximum profit to the company. 

● A book recommendation system is a type of recommendation system where we have to recommend similar type of books to the reader based on his interest. The books recommendation system is used by online websites which provide ebooks  like google play books, open library, good Read’s, etc. 

● As we can see, after implementing Collaborative Filtering and evaluating it using SVD matrix , We got a recall rate of around 97 for hit@15 is pretty good. 
