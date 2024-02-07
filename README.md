# Min Hashing

## Objective

Utilizing a News Corpus dataset containing news articles from three distinct categories, apply the min-hashing technique to establish similarity relationships between the articles.

## Dataset

The dataset chosen for this problem is the AG News Classification Dataset, which is available on Kaggle. The dataset can be accessed using the following link: [Dataset].

The dataset consists of 4 classes, and each class consists of 30,000 news items. The dataset is visualized in Figure 1. As we only need three categories for this assignment, we exclude news items of category 3. Additionally, the number of data items is reduced to 100 per category, as specified by the assignment. The visualization is in Figure 2. The number of characters per document is visualized in Figure 3.

## Conclusion
From the plots below, the following inferences can be drawn:
1. The shapes of the plots for the column-column matrix and signature matrices are
similar. This shows that we can effectively capture similarity using Signature Matrices.
2. The captured similarity values are inversely proportional to the value of k. In other
words, the similarity values are highest for k=5 and decrease as we increase the value
of k.
3. Increasing the percentage of min-hashing results in a slight increase in the captured
similarity values.
4. Items of Category 1 are similar to each other while items of Category 3 are similar to
each other.
