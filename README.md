# Top 5000 Songs Dataset

This dataset contains details of the top 5000 songs based on popularity. It’s mainly intended for analysis and experimentation with music-related data.

Each row corresponds to one song, along with information about the artist and various song attributes.

Columns

The dataset includes a mix of metadata and audio features, such as:

Song name

Artist

Album

Genre

Popularity / ranking

Release year

Duration

Audio features like energy, danceability, tempo, loudness, etc.

Some fields may be missing or inconsistent, especially genre-related columns.

Notes on the data

The ranking reflects popularity at the time the data was collected

Popularity should be treated as relative, not absolute

Genre labels are not always reliable and may overlap

The dataset isn’t perfectly clean and hasn’t been over-engineered on purpose.

Use cases

This dataset can be used for:

Exploratory data analysis

Visualisation

Machine learning tasks (clustering, prediction, recommendation)

General practice with real-world data

Format

The data is provided as a CSV file and can be loaded using standard tools such as pandas or spreadsheet software.
