# Data Science Projects

This workspace contains four exploratory data analysis projects built with Python, pandas, NumPy, and Jupyter notebooks.

## Projects

### Investigating Netflix Movies
Folder: [Investigating Netflix movies](Investigating%20Netflix%20movies)

This project analyzes `netflix_data.csv` to explore movies released in the 1990s. The notebook focuses on two questions:

- What was the most frequent movie duration in the 1990s?
- How many short action movies were released in the 1990s?

The analysis filters the dataset to 1990s movies, finds the most common duration, and counts short action films.

### Exploring NYC Public School Test Result Scores
Folder: [Exploring NYC Public School Test Result Scores](Exploring%20NYC%20Public%20School%20Test%20Result%20Scores)

This project analyzes `schools.csv` to study NYC public school SAT performance. The notebook answers three questions:

- Which schools have the best math results?
- Which are the top 10 schools based on combined SAT scores?
- Which borough has the largest variation in combined SAT performance?

The analysis builds summary tables for best math schools, top combined SAT scores, and borough-level SAT statistics.

### Analyzing Crime in Los Angeles
Folder: [Analyzing Crime in Los Angeles](Analyzing%20Crime%20in%20Los%20Angeles)

This project analyzes `crimes.csv` to help the LAPD identify patterns in criminal behavior and allocate resources effectively. The dataset (a modified version of the publicly available Los Angeles Open Data crime records) includes the reported/occurrence dates, time, area, crime description, victim age/sex/descent, weapon, status, and location. The notebook answers three questions:

- Which hour has the highest frequency of crimes? (stored as `peak_crime_hour`)
- Which area has the largest frequency of night crimes, committed between 10pm and 3:59am? (stored as `peak_night_crime_location`)
- How many crimes were committed against victims in each age group (0-17, 18-25, 26-34, 35-44, 45-54, 55-64, 65+)? (stored as the `victim_ages` Series)

The analysis derives a "Crime Hour" column from the time of occurrence, uses a count plot to visualize hourly frequency, filters night-time crimes to find the peak area, and bins victims into age categories.

### Visualizing the History of Nobel Prize Winners
Folder: [Visualizing the History of Nobel Prize Winners](Visualizing%20the%20History%20of%20Nobel%20Prize%20Winners)

This project analyzes `data/nobel.csv` (winners from 1901 to 2023, sourced from the Nobel Prize API) to explore patterns among laureates. The notebook answers several questions:

- What is the most commonly awarded gender and birth country? (stored as `top_gender` and `top_country`)
- Which decade had the highest ratio of US-born Nobel Prize winners to total winners? (stored as `max_decade_usa`)
- Which decade and category combination had the highest proportion of female laureates? (stored as `max_female_dict`)
- Who was the first woman to receive a Nobel Prize, and in what category? (stored as `first_woman_name` and `first_woman_category`)
- Which individuals or organizations have won more than one Nobel Prize? (stored in `repeat_list`)

The analysis computes per-decade US-born and female proportions, plots trends with Seaborn relplots, and identifies repeat winners.

## Files

- [README.md](README.md)
- [Investigating Netflix movies/notebook.ipynb](Investigating%20Netflix%20movies/notebook.ipynb)
- [Investigating Netflix movies/netflix_data.csv](Investigating%20Netflix%20movies/netflix_data.csv)
- [Exploring NYC Public School Test Result Scores/notebook.ipynb](Exploring%20NYC%20Public%20School%20Test%20Result%20Scores/notebook.ipynb)
- [Exploring NYC Public School Test Result Scores/schools.csv](Exploring%20NYC%20Public%20School%20Test%20Result%20Scores/schools.csv)
- [Analyzing Crime in Los Angeles/notebook.ipynb](Analyzing%20Crime%20in%20Los%20Angeles/notebook.ipynb)
- [Analyzing Crime in Los Angeles/crimes.csv](Analyzing%20Crime%20in%20Los%20Angeles/crimes.csv)
- [Visualizing the History of Nobel Prize Winners/notebook.ipynb](Visualizing%20the%20History%20of%20Nobel%20Prize%20Winners/notebook.ipynb)
- [Visualizing the History of Nobel Prize Winners/data/nobel.csv](Visualizing%20the%20History%20of%20Nobel%20Prize%20Winners/data/nobel.csv)
