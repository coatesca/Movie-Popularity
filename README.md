# Movie Popularity

In the film industry, as with most other entertainment industries, it is important to mitigate costs and maximize profit. As most film professionals know, and even non-professionals, making films is expensive. Having the best director and an infinite budget does not necessarily guarantee a blockbuster. Thus, the current dataset exploration and models aim to discover what features contribute to films with higher revenues. This is for the benefit of future filmmakers and producers who may tailor their tactics to meet consumer demands more econonmically. 

To explore this issue, data from The Movie Database (TMDB) and The Internet Movie Database (IMDB) were used. Such databases include vital film features such as Budget, Revenue, Runtime, and Vote Average. Though the databases cover a wide variety of media types, only movie information was used. 

Since the feature of interest, Revenue, is a variable without discrete classes, only the unsupervised models KMeans and DBSCAN were used. Features such as Vote Average and Budget were especially of interest, and ultimately for the KMeans model were important predictors when sorting films into clusters. The DBSCAN model was more particular in its cluster division, creating over four times the number of clusters as the KMeans model, with little distinction in mean Revenue in some clusters. As a result of its conciseness and efficiency, the KMeans model was fit on new data. It predicted a film with a higher budget, but a lower vote average, to fit in a cluster with other mid-range performing films. 

Since the dataset is too large for github, the link is provided below. 

Dataset link: https://www.kaggle.com/datasets/ggtejas/tmdb-imdb-merged-movies-dataset/data
