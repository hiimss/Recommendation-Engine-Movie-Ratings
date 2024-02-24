The folder contains the following elements:
 -  data
    This folder contains the raw data provided for this project
 0. Multi-armed Bandit.ipynb
    This file contains 
        1. The data preprocessing as well as the feature engineering process for the raw data. 
            The processed data is grouped into 4 groups as per project requirement, as stored in the directory 'processed_data'.
        2. The hyper-parameter selection for epsilon in the epsilon-greedy algorithm
            In this process, the performance of 3 selected values of epsilons: 0.03, 0.05 and 0.10 are compared against each other. 0.05 is selected for further analysis.
 1. Female_Young.ipynb
    This file contains 5 iterations of the epsilon-greedy algorithm on the processed rating data for the Female, Young group.
    In each iteration, the movie with the highest percentage of being selected is the best movie to be recommended. We stored the movie title, remove its relevant ratings data in the dataset and enter the next iteration.
 2. Female_Adult.ipynb
    This file contains 5 iterations of the epsilon-greedy algorithm on the processed rating data for the Female, Adult group.
    In each iteration, the movie with the highest percentage of being selected is the best movie to be recommended. We stored the movie title, remove its relevant ratings data in the dataset and enter the next iteration.
 3. Male_Young.ipynb
    This file contains 5 iterations of the epsilon-greedy algorithm on the processed rating data for the Male, Young group.
    In each iteration, the movie with the highest percentage of being selected is the best movie to be recommended. We stored the movie title, remove its relevant ratings data in the dataset and enter the next iteration.
 4. Male_Adult.ipynb
    This file contains 5 iterations of the epsilon-greedy algorithm on the processed rating data for the Male, Adult group.
    In each iteration, the movie with the highest percentage of being selected is the best movie to be recommended. We stored the movie title, remove its relevant ratings data in the dataset and enter the next iteration.
 5. Evaluation.ipynb
    This jupyter notebook reads the recommended best 5 movies, as well as the processed ratings data for the 4 groups and evaluate respectively.
    The evaluation is based on the percentage overlap between the 5 recommended movies and the 5 most liked movies in each group.
 -  processed_data
    This folder contains the processed data.
 -  output
    This folder contains the algorithm outputs, including results of the 5 iterations of the epsilon greedy algorithm and the final 5 recommendations record for each group.

To execute the codes, open and run the ipynb files in the sequence listed above.
