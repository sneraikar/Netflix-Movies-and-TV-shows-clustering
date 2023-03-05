# Netflix-Movies-and-TV-shows-clustering

📖 Introduction


The project aims to cluster the video content available on Netflix based on the company’s site data. Apart from aiding in the development of an efficient recommendation system, clustering the video content would also provide information about the type of content the company is interested in listing on its site. Thus giving an insight to content creators and filmmakers on the type of video content in demand.



📖About the dataset


This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flexible which is a third- party Netflix search engine.
In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.


![wp5063348](https://user-images.githubusercontent.com/80422212/200168358-cca94047-febc-409b-b137-340cb59b6e9f.jpg)
📖 EDA Observations

* Majority of content available on Netflix is Movies.
* In recent years though many TV shows have been added, number Movies outpower the number of TV shows.
* United States and India top the countries that produce all of the available content on Netflx.
* TV-MA tops the graphs,indicating that mature content is more popular on Netflix.Then to perform clustering based on matching text features - Unsupervised Machine learning models were used.
![image](https://user-images.githubusercontent.com/80422212/222959128-1d4e5f27-11aa-478e-8245-f9f59066e4d1.png)




📖 ML Models Trained and Evaluated
DBSCAN
K-Means
Hierarchical

Show id: Unique ID for every Movie / TV Show
type – Identifier - A Movie or TV Show title – Title of the Movie / TV Show director-director of the content
cast –Actors involved in the movie / show country – Country where the movie / show was produced
date_added – Date it was added on Netflix release_year – Actual Release year of the movie / show
rating – TV Rating of the movie / show duration – Total Duration - in minutes or number of seasons
listed_in – genre
description – The Summary description
