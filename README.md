# Load-data-into-the-IBM-Db2-database-from-a-CSV-file
The dataset I used in this project comes from the following source: https://www.kaggle.com/antfarol/car-sale-advertisements under a CC0: Public Domain license. 
The steps below show how I load the dataset into instance of IBM Db2 on Cloud.
[Screenshot (370)](https://user-images.githubusercontent.com/108270900/215720905-b4413618-d779-4fdb-8dc0-1ea83b364f57.png)
I click on LOAD > LOAD DATA and open the downloaded csv file.
Click next to select a SCHEMA from a list of schema names.![Screenshot (372)](https://user-images.githubusercontent.com/108270900/215722044-50dab9d0-c029-4966-a6e3-b466b7a3dd0b.png)
I then click on NEW TABLE and name it CARSALESTABLE, after which I click on BEGIN LOAD to begin the process of loading the data from the CSV into your database.
 
![Screenshot (373)](https://user-images.githubusercontent.com/108270900/215722595-543dd30a-2aa4-4978-aaf3-ff1e987d6fb4.png)
![Screenshot (374)](https://user-images.githubusercontent.com/108270900/215722680-902406ed-3ce5-4b9d-acae-11acb18d8863.png)
And finally Data from CSV file is now loaded into your Db2 instance
