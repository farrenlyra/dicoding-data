# Dicoding Final Project Data Analytics - Bike Sharing Rentals

To complete the final task of the "Belajar Analisis Data Dengan Python" course on Dicoding, I conducted an analysis process that includes Data Wrangling, Exploratory Data Analysis (EDA), and Data Visualization of a dashboard from the bike sharing dataset. You can check out the Streamlit [here](https://dashboardbicycle.streamlit.app/).

- **Data Wrangling**: I began by cleaning and preparing the dataset. This involved removing unnecessary columns, renaming variables for clarity, and transforming categorical data into meaningful labels.

- **Exploratory Data Analysis (EDA)**: I examined the data to uncover trends and insights. This stage helped in understanding the distribution of data, identifying outliers, and summarizing key statistics.

- **Data Visualization**: Finally, I created various visualizations such as bar charts and line plots to present the results, making it easier to interpret trends in bike rentals across different months, seasons, weather conditions, and more.

In the README, I'll explain these steps in detail, showcasing how the analysis leads to the analysis from the bike sharing dataset. 

## 1. File Structures
```
.
├── dashboard
│   ├── dashboard.py
│   └── day.csv
├── data
│   ├── Readme.txt
│   ├── day.csv
|   └── hour.csv
├── screenshots
|   ├── Screenshot (1).png
|   ├── Screenshot (2).png
|   ├── Screenshot (3).png
|   └── Screenshot (4).png
├── README.md
├── notebook.ipynb
└── requirements.txt
```

## 2. Project work cycle
1. Data Wrangling: 
 - Gather the data
 - Assess the data
 - Clean the data
2. Exploratory Data Analysis:
 - Defined business questions
 - Create data exploration
3. Data Visualization:
 - Create data visualization for the business questions
4. Dashboard:
 - Create filter components on the Streamlit dashboard
 - Fill the dashboard with various data visualizations

**Note: Numbers 1 to 3 are in the dicoding-collection-exercise and number 4 is in dashboard.**

## 3. Getting Started
### `notebook.ipynb`
1. Download this project.
2. Open Google Colaboratory.
3. Create a new notebook for this project.
4. Upload and select this exact file.
5. Wait until it's connected to the runtime.
6. The last but not least, run the code.

### `dashboard/dashboard.py`
1. Download this project.
2. Install Streamlit and the other libraries. (don't move the csv file because it acts a data source. keep it in one folder as dashboard.py)
3. Open VSCode then you can run the file by clicking the terminal and write the code `streamlit run dashboard.py` to run the dashboard.

## 4. Screenshots

![alt text](https://github.com/farrenlyra/dicoding-data/blob/0e609a789e052c9bda82c5acc3bd1df6a1ff636f/screenshots/Screenshot%20(1).png)

![alt text](https://github.com/farrenlyra/dicoding-data/blob/0e609a789e052c9bda82c5acc3bd1df6a1ff636f/screenshots/Screenshot%20(2).png)

![alt text](https://github.com/farrenlyra/dicoding-data/blob/0e609a789e052c9bda82c5acc3bd1df6a1ff636f/screenshots/Screenshot%20(3).png)

![alt text](https://github.com/farrenlyra/dicoding-data/blob/0e609a789e052c9bda82c5acc3bd1df6a1ff636f/screenshots/Screenshot%20(4).png)
