Top 5000 Songs Analysis
Project Overview

This project focuses on exploring and analysing a dataset of the top 5000 songs using metadata and audio features. Rather than optimising for a single predictive task, the aim was to understand patterns in popular music, examine how different features relate to each other, and observe how song characteristics vary across artists, genres, and time.

Dataset

The dataset consists of approximately 5000 songs ranked by popularity at the time of collection. Each entry represents a single song and includes metadata such as song title, artist, album, release year, genre, popularity score, and duration. In addition, the dataset contains audio features such as danceability, energy, tempo, loudness, and related measures. Some fields contain missing or inconsistent values, particularly genre-related columns, reflecting the nature of real-world music data.

Problem Context

The dataset was used primarily for exploratory analysis and modelling tasks, such as identifying trends in popular music and grouping songs based on shared characteristics. Depending on the analysis, tasks can be framed as regression, clustering, or classification problems using the available numerical and categorical features.

Data Preprocessing

Basic data cleaning and preprocessing were performed before analysis. This included handling missing values, converting duration into a consistent numeric format, and encoding categorical variables where required. Numerical features were scaled when used in modelling to ensure fair comparison across different feature ranges.

Analysis and Modelling

Various exploratory techniques were applied to understand distributions, correlations, and trends within the data. Modelling approaches such as clustering and regression can be applied to group similar songs, predict popularity, or analyse how audio features influence listener preferences. Emphasis was placed on interpretability and understanding feature behaviour rather than maximising predictive performance.

Observations

Initial analysis shows that a small number of audio features tend to explain a large proportion of the variation in the data. Features related to tempo, energy, and loudness often dominate patterns, while genre labels are less consistent and sometimes ambiguous. This highlights the limitations of categorical music labels and the usefulness of continuous audio features.

Libraries

This project was implemented in Python using Pandas and NumPy for data manipulation, Scikit-learn for preprocessing and modelling, and Matplotlib or Seaborn for visualisation during exploratory analysis.

Conclusion

This project demonstrates how music data can be analysed using standard data science techniques to uncover trends and patterns in popular songs. Rather than focusing solely on model performance, the project emphasises data understanding, feature influence, and the practical challenges of working with real-world datasets.
