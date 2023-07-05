# Hybrid-Recommender-System

# Business Problem
- It is requested to make 10 film recommendations using item-based and user-based recommender methods for the user whose ID is given.

# Dataset Story
- It contains films and the ratings given to these films.
- The data set contains about 2000000 ratings for about 27000 films.
  # The dataset consists of two csv files
    # 1st csv file: film.csv file
      - movield: Unique film number
      - title: Film name
      - genres: Type
    # 2nd csv file : rating.csv file
      - userid = Unique user number.
      - movield = Unique film number
      - rating = Rating given to the film by the user
      - timestamp = Evaluation date
# Road Map
- 1. Preparation of Data Set
- 2. Determining the Films Watched by the User to Make Suggestion
- 3. Accessing Data and Ids of Other Users Watching the Same Films
- 4. Determining the Users Most Similar to the User to Make Suggestion
- 5. Calculation of Weighted Average Recommendation Score
- 6. Item-Based Recommendation
