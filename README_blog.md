Blog
 
| Date       | Description                                                                                                                  |
|------------|------------------------------------------------------------------------------------------------------------------------------|
| 03-11-2024 | - Data cleaned with 3747 unique users, 61233 unique movies                                                                   |
|            | - Collaborative filtering phase with User-item matrix sparsity 99.96%                                                        |
|            | - Used isolation forest and the user/film below average to filter users and filmls                                           |
|                                                                                                                                           |
| 11-11-2024 | - New dataset with 8686 unique users, 91248 unique movies                                                                    |
|                                                                                                                                           |
| 12-11-2024 | - Use collaborative filtering with SVD to recommend films (5 films per user)                                                 |
|            | - Facing long computaion time problem while using train and test                                                             |
|                                                                                                                                           |
| 15-11-2024 | - Finish Phase 1: Collaborative filtering methods                                                                            |
|            | - Filter the user who have more than 2 watched days (the last watched day as test set)                                       |
|            | - Split the train and test set, we get 8491 unique users, 90418 uinqiue movies in the train set                              |
|            | - Filter users and film by isoation forst and manuanl method --> final data with 5624 unique users and 483 films             |
|            | - Models: Similarity, SVD, Clustering, Matrix Factorizaiton, Association Rules                                               |
|            | - Results: high sparity 95%, low accuracy 1%.                                                                                |

