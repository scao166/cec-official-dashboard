# Cryptocurrency Energy Consumption Visualization
The consumption demo is deployed on Heroku. The link is [here](https://cecv.herokuapp.com/)

### What is this project?

This is a web application to convert cryptocurrency energy consumption data into graphs and present them in an intuitive and interactive way. In CECV, we present two data sets including the **BECI** (Bitcoin Energy Consumption Index) and **EECI** (Ethereum Energy Consumption Index). 

According to the **BECI** from ***Digiconomist***, the peak value of the annual electricity consumption reached 77.782TWh, which is comparable to the power consumption of Chile. Besides, **the generated annual carbon footprint** is nearly 36.95 Mt of carbon dioxide, comparable to the carbon footprint of New Zealand. Moreover, **the electricity consumption of a single transaction** is 761.93 kWh, which is close to the energy consumption of 700,000 VISA payments and is equivalent to the 20-day average electricity consumption of American households, and the **e-waste generated** by each transaction is 101.10 grams.

As for the **EECI**, the annual total **electrical energy consumption** of Ethereum is 11.89 TWh, which is comparable to the power consumption of Uruguay, and the footprint per single transaction is 29.44 kWh, equivalent to the power consumption of an average U.S. household over 0.99 days.

### How to run?

1. Download and Install the latest version of NodeJS

    The NodeJs official download link is [here](https://nodejs.org/en/download/)
    
2. Download the latest version of project

   ```
   $ git clone https://github.com/scao166/cec-official-dashboard.git
   ```

3. Install application dependencies from git repositories:

   ```
   $ npm install
   ```

4. Run the application locally

   ```
   $ npm start
   ```

### About the Project 

- [ReactJs](https://github.com/facebook/react) (User Interface)

- [Lodash](https://lodash.com/) (JavaScript Utility Library)

- [HighCharts](https://github.com/highcharts/highcharts) (Data Visualization)

- [D3](https://github.com/d3/d3) (Data Visualization)

- [Python3](https://www.python.org/) (Data Processing and Analysis)

- [Digiconomist](https://digiconomist.net/) (Data Source)

- [BECI](https://github.com/ChenHuangyin/CECV/raw/master/src/data/BECI.csv), [EECI](https://github.com/ChenHuangyin/CECV/raw/master/src/data/EECI.csv) (Data Source)

  



