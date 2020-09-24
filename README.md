<img src="https://raw.githubusercontent.com/codecaviar/digital_asset_management/master/assets/bingyune-and-company-logo-6400x3600.png" align="left" width="200" height="auto">

<br/><br/><br/><br/>

----------

# The Final Countdown: 8 Essential Steps for Data Science

**Code Caviar Story**: https://www.bingyune.com/blog/final-countdown-music    

## Project Overview

"Data Science" is a modern extension of mathematics and statistics that people have been doing for centuries - long before phrases such as "Big Data" and "Deep Learning" came on the scene. At its core, data science requires the same skills of using information available to gain insight and improve processes. Whether you are exploring a small Excel spreadsheet or 1 billion records in a SQL database, the goals for data scientists are always the same: explain values and predict future trends. Data scientists achieve these goals by applying NumPy, Pandas, Matplotlib, Scikit-Learn, and an all-you-can-eat buffet of other popular libraries. NumPy is used for lower-level scientific computation. Pandas is built on top of NumPy and designed for practical data analysis in Python. Matplotlib is the foundation for many other plotting libraries and plotting support in higher-level libraries such as Pandas. Scikit-Learn comes with many machine learning models that you can use out of the box. In this Beginner's Guide, the focus will be approaching data science from scratch by summarizing the most common and useful functionality from these libraries.

**The goal of this project is to provide a Beginner's Guide on the main hacking skills needed to start doing data science.** The project makes use of data sourced from the [Billboard Archives](https://www.billboard.com/charts). The original dataset contains more than 300 songs and weekly ratings from the year 2000 - artist name, track name, song length, genre, first appearance, and week of highest rating, and weekly ratings from the Billboard Top 100 Chart. Billboard Charts and all Billboard assets are the property of Billboard-Hollywood Reporter Media Group, a division of Eldridge Industries.

## Summary:

* Importing Data - bring data into your workbook
* Selecting & Combining Data - select a single element or a certain subset of the data
* Exploring Data - after importing your data
* Filtering & Sorting Data - help with data exploration to find value
* Cleaning Data - especially helpful when working with real-world data
* Visualizing Data - create static, animated, and interactive visualizations
* Writing Data - export your data from your workbook
* Machine Learning - methods for training and applying models

Programming languages like Python are used at every step in the Data Science process. For example, your data science workflow might include the following steps: First, you start with Python and the Pandas library to read a csv file with data you need from a public database. You then clean and sort the data into a dataframe (table) that's ready for analysis. Next, using Python and the Pandas and Matplotlib libraries, you begin analyzing, exploring, and visualizing the data. After learning more about the dataset through your exploration, you use Python and the Scikit-Learn library to build a model that predicts future outcomes based on the data you pulled. There are lots of other free Python for data science tutorials out there (just like this one), so be sure to find resources that'll teach you interactively, with a curriculum that's been constructed to guide you through your data science learning journey.

## Getting Started

Cloning the git repository and installing the provided packages will help you get a copy of the project up and running on your local machine. The analysis for this project was performed using Jupyter Notebook (.ipynb) and the packages were managed using the Anaconda platform.

```
git clone https://github.com/codecaviar/final_countdown_music.git
conda env create -f environment.yml
```

File Description:
* environment.yml - packages used to perform this analysis
* notebook_final_countdown_music.ipynb - Jupyter Notebook for this project including data wrangling and exploratory data analysis     
* billboard.csv - contains more than 300 songs and weekly ratings from the year 2000 on the Billboard Top 100 Chart

## Authors

- **BingYune Chen** - [LinkedIn](https://www.linkedin.com/in/bingyune-chen/)
- **BingYune & Co** - [GitHub](https://github.com/codecaviar)

## License

The project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

The project referenced the following:
* https://chrisalbon.com/#python
* https://elitedatascience.com/python-cheat-sheet

----------
The Code Caviar is a digital magazine about data science and analytics that dives deep into key topics, so you can experience the thrill of solving at scale.
