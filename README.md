# Welcome to My GitHub!

## About Me

Hi!  I'm Connor, a Computer Science major, Statistics and Economics double minor at UC Irvine.  My main technical interests come through analyzing data, as well as recently I have gotten into reading about options trading, and the math that comes with that.  My GitHub will show some of the projects I have made either in school or on my own.

## My Projects

### Machine Learning

[Predicting UCL Injuries Among MLB PLayers](https://github.com/Haxor48/CS184A_Final_Project)

A project done with a partner from class in which we took pitcher metrics from both the websites Fangraphs and Baseball Savant, as well as a list of a history of Ulnar Collateral Ligament (UCL) Injuries in MLB players and tried to predict future injuries looking at metrics.  We broke the study down into short-term and long-term experiments, in which the short-term took pitch-by-pitch game data and turned it into game-by-game differences for each pitch for each pitcher, whereas the long-term looked at season-long metrics for each pitcher.  For the long-term, we used multiple algorithms/models, including K-Nearest Neighbors, Logistic Regression, a Multi-layered Perceptron, and a Convolutional Neural Network to make predictions, whereas for the short-term we utilized a Recurrent Neural Network to make predictions.  We then wrote a [final project report.](https://haxor48.github.io/predicting_ucl_injuries/)

[Optimizing Neural Network Hyperparamters Using Various Optimization Methods](https://github.com/Haxor48/Neural-Network-Hyperparameter-Optimization)

Another class project where we utilized random subsampling as well as 2nd derivative optimization methods as a way to speed up the training process and find an efficient local optimum of hyperparameters, providing a search that is automatic (avoids searching for hyperparameters yourself manually) but also runs in far faster time than that of a search like grid search which uses brute force. We then tested our data on 3 example data sets that were mixes of classification and regression problems to see how accurate and efficient the models were.

[Using Reinforcement Learning to Trade Stocks](https://github.com/Haxor48/Reinforcement-Learning-Stock-Trader)

In this project, we pulled data from the S&P 250 stocks and then used Proximal Policy Optimization (PPO) methods on an environment pulled from FinRL to try and recreate certain portfolio strategies and see how effective they are. We also utilized multiprocessing to speed up our training process, as we used so much data from years of 250 stocks' prices.

[Testing the Effects of Biased Subsampling on Various Machine Learning Models](https://github.com/Haxor48/Biased-Sampling-On-Machine-Learning-Models)

In this project, me and others created a biased subsampler on a classification dataset (Ex: Make it so the data is 70% False, 30% True) and tested to see how it would affect the accuracy of various machine learning models. The models we tested on were K-Nearest Neighbors, a Logistic Classifier, a Neural Network, and the kMeans algorithm.

### Artificial Intelligence/Algorithms

[Creating a Local Search Engine Using Lemmatization and Ranking Algorithms](https://github.com/Haxor48/local-corpus-search-engine)

A class project where we made our own search engine (with a UI) that uses multi-token lemmatization and then a ranking algorithm to search a dataset from UC Irvine web links efficiently.

[C++ Minesweeper AI](https://github.com/Haxor48/Cpp-Minesweeper-AI)

A project with someone else where we used C++ and different artificial intelligence algorithms such as Constraint Satisfaction Problems, Backtracking Search, Local Search, and Markov Decisions to find either the optimal decision or choose a decision with the highest chance of success, with the general goal of having the AI win games of Minesweeper.

### Websites

[Discoverify](https://github.com/Haxor48/discoverify)

A website where you can log in (doesn't currently work as I wasn't able to get approval for usage of the Spotify API) and view your most played artists and songs.  The website also recommends new artists via an algorithm, where you can like and dislike the recommended artists to further influence new recommended artists.

[Artificial Scout](https://github.com/Haxor48/mlb_predict)

A website that displays player and team statistics using the pybaseball API.  The website also then uses TensorFlow machine learning to predict future player stats using their past aggregate stats and more advanced batted/pitched ball data.

### Data Analysis

[2020 Election Data Aggregation](https://github.com/Haxor48/2020ElectionData)

A small project to practice Excel functions where I aggregated data from the 2020 Election, of which I got from MIT's election data page.  I looked at county, statewide, senate, congressional, presidential, etc data.

[NBA Players Return Write-up](https://github.com/Haxor48/nba-players-return)

A write-up I did using the nbastatR package where I did a what-if scenario where every NBA player returned to the original team with their draft pick. I analyzed which teams would improve, as well as covered and explained certain NBA statistics to a more common fan.

### Game Design

[Price Cut](https://github.com/Haxor48/InteractiveHorrorGame)

A game I worked on for a Senior year capstone project in High School with others.  This game was developed in Unity, in which you had places to go inside a grocery store, but you the player couldn't make too much noise to bring the enemy closer, as you had to manage the in and out of game noise levels to beat this horror game.

[50XM](https://github.com/Haxor48/50xx-the-mod)

This was a Smash Bros Ultimate mod I developed with others (though primarily by myself) in the language Rust.  I edited character and overall game mechanics to make the game more enjoyable for the players.
