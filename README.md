
# Movie recommendation system using collaborative filtering.
Implemented it using 3 ways-User-user,item-item & matrix factorization(using svds)

User has to pick and rate any 4 movies(on scale of 1 to 5) out of assorted and diversified collection of 300 movies he/she watched previously.Based on this input, system recommends 4 more movies that should be similar to his/her interests.

Data of 300 movies has been scraped from IMDBs site.Also,130 real-world users actual ratings have been used instead of dummy/fake ones in the algos(thanks to GroupLens Research for this).

########################Thanks to these References #######

http://recommender-systems.org/collaborative-filtering/

https://en.wikipedia.org/wiki/Collaborative_filtering

https://towardsdatascience.com/various-implementations-of-collaborative-filtering-100385c6dfe0

https://www.analyticsvidhya.com/blog/2016/06/quick-guide-build-recommendation-engine-python/


https://pandas.pydata.org/pandas-docs/stable/

https://docs.scipy.org/doc/scipy/reference/generated/scipy.sparse.linalg.svds.html

https://data36.com/pandas-tutorial-3-important-data-formatting-methods-merge-sort-reset_index-fillna/
