<img src="https://upload.wikimedia.org/wikipedia/commons/1/1a/Goodreads_logo.svg" alt="Pandas" align="center" width="100"/>

# Goodreads: Book rating prediction

### Project objective
The objective of this project is to train a model that predicts the rating of a book. This will involve performing exploratory analysis of the dataset, feature engineering and selection, as well as model training and evaluation.

### The dataset
The dataset used for this project is a collection of books from Goodreads, which has been curated using real user information. This dataset can be found on [Kaggle](https://www.kaggle.com/datasets/jealousleopard/goodreadsbooks).

#### Dataset features:
1. bookID: A unique identification number for each book.
2. title: The name under which the book was published.
3. authors: The names of the authors of the book. Multiple authors are delimited by “/”.
4.  average_rating: The average rating of the book received in total.
5. isbn: Another unique number to identify the book, known as the International Standard Book Number.
6. isbn13: A 13-digit ISBN to identify the book, instead of the standard 11-digit ISBN.
7. language_code: Indicates the primary language of the book. For instance, “eng” is standard for English.
8. num_pages: The number of pages the book contains.
9. ratings_count: The total number of ratings the book received.
10. text_reviews_count: The total number of written text reviews the book received.
11. publication_date: The date the book was published.
12. publisher: The name of the book publisher.

### Models used:
* Linear regression
* Decision Tree
* Random Forest
