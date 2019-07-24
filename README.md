# Clothing-Review-Sentiments

The current reality of the apparel industry is that less and less consumers are frequenting brick and mortar establishments. Customers are finding themselves drawn more towards online shopping and e-commerce for its ease and convenience. A unique problem that is arising from e-commerce, particularly for the apparel industry, is how customers are deciding on specific products without physically seeing, touching, or trying on articles of clothing. As a result, reviews are the go-to resource when making decisions on whether to buy something or not. Reviews are not only important for consumers, but also for any online retail. They rely on reviews to generate interest and profit on a particular item. 

Reviews can be extensive and oftentimes contain irrelevant information. Can we compress the data to improve the product? Can we take the reviews and predict whether an item will get recommended or not? From reviews, online retailers can improve the quality of their product to satisfy consumers and increase profit and credibility.

# Summary

- Dresses, knits, and blouses are the most reviewed and recommended items. On average, they receive pretty good positive feedback as well.

- Majority of these female consumers range from ages 30-40; however their age doesn't really show any influence in their clothing ratings.

- Overall metrics shows that Afinn is a slightly better sentiment analyzer than Textblob.

- Applying sentiment from Afinn and Textblob as part of the many input variables, we see that one with the most influence in the machine learning models are: Label_pos, Rating, Label_neutral, Sent_af_pos, and Sent_tb_pos.

- Comparing the three machine learning models (Naive Bayes, Random Forest Classifier, and Logistic Regression), we see that Logistic Regression is the best model for predicting whether these women will recommend an item or not.
