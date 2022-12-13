## Project. Research of advertisements for the sale of apartments
### Short description
At the disposal of the data service Yandex.Realty - an archive of ads for the sale of apartments in St. Petersburg and neighboring settlements for several years. You need to learn how to determine the market value of real estate. Your job is to set the parameters. This will allow to build an automated system: it will track anomalies and fraudulent activity.

Two types of data are available for each apartment for sale. The first ones are entered by the user, the second ones are obtained automatically on the basis of cartographic data. For example, the distance to the center, airport, nearest park and reservoir.

### Content of the project
1. Exploring general information about the data
2. Data preprocessing:
     - identification and study of missing values
     - casting data to the required types
3. Calculate and add to the table:
     - price per square meter;
     - day of the week, month and year of publication of the announcement;
     - floor of the apartment; options - first, last, other;
     - the ratio of residential and total area, as well as the ratio of kitchen area to total.
4. Conduct an exploratory data analysis and analyze:
     - Dependence of the area on the price of the apartment
     - Dependence of distance from the center and the price of the apartment
     - Dependence of the number of rooms and the price of the apartment
     - Dependence of the type of number of storeys of the apartment and the price of the apartment
     - Dependence of the day of the week, month, year and apartment price

### Libraries used in the project:
- pandas
- matplotlib
