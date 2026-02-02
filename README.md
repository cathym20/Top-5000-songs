---

## Top 5000 Songs Analysis

---

### Project Overview

This project focuses on exploring and analysing a dataset of the top 5000 songs using metadata and audio features. Rather than optimising for a single predictive task, the main objective was to understand patterns in popular music, examine how different features influence song characteristics, and observe how these patterns vary across artists, genres, and time.

---

### Dataset

The dataset consists of approximately 5000 songs ranked by popularity at the time of data collection. Each entry represents a single song and includes metadata such as song title, artist, album, release year, genre, popularity score, and duration. The dataset also contains audio features including danceability, energy, tempo, loudness, and related measures. Some columns contain missing or inconsistent values, particularly genre-related fields.

---

### Problem Context

The dataset was primarily used for exploratory analysis and modelling tasks. Depending on the approach, problems can be framed as clustering, regression, or classification tasks using a combination of numerical and categorical features.

---

### Data Preprocessing

Basic data cleaning and preprocessing were performed before analysis. This included handling missing values, converting duration into a consistent numeric format, and encoding categorical variables where required. Numerical features were scaled when used in modelling to ensure comparability across features.

---

### Analysis and Modelling

Exploratory analysis was used to study distributions, correlations, and trends within the data. Modelling techniques were applied to group similar songs, analyse relationships between audio features, and examine factors associated with popularity. The focus was on understanding feature behaviour rather than maximising model performance.

---

### Observations

The analysis shows that a small number of audio features explain a large proportion of the variation in the dataset. Features related to energy, tempo, and loudness tend to dominate patterns, while genre labels are less consistent and often overlap. This highlights the limitations of genre-based categorisation in music data.

---

### Libraries

This project was implemented in Python using Pandas and NumPy for data handling, Scikit-learn for preprocessing and modelling, and Matplotlib for visualisation during exploratory analysis.

---

### Conclusion

This project demonstrates the application of data analysis techniques to music data, with an emphasis on understanding patterns, feature influence, and real-world data limitations rather than focusing solely on predictive performance.

---

