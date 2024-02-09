Home Sales
GitHub release (3.11.4) 
GitHub last commit 2/9/2024
Author: Arpita Sharma

Project Overview
This is the Module 22 Challenge for the Data Analytics UC Berkeley 2023 Bootcamp called Home Sales. In this challenge, I am using my knowledge of SparkSQL to determine key metrics about home sales data. Then I use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

Installation and Setup
To view this project, download the .ipynb file and upload to Google Colab to view. 

I like to structure it as below -

Codes and Resources Used

Editor Used: Google Colab 
Python Version: 11.3

Python Packages Used

General Purpose: os, findspark
Data Manipulation: pyspark functions

Data
Below are details about the data used for the project

Source Data
Data on home sales from AWS S3 Bucket: "https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.2/22-big-data/home_sales_revised.csv"

Code structure
One main .ipynb file is used for this project, along with license and readme.

Here is the basic suggested skeleton for your data science repo (you can structure your repository as needed ):

├── data
├── LICENSE
├── README.md

Results and evaluation
For the challenge, I read in data for homesales and ran queries using pyspark to answer several questions about the home sales data. I also cached the data and created a temporary table with a partition and compared the time required for all three approaches. I found that caching the data and running a sql query on it was significantly faster than the other two approaches. 

License
For this github repository, the License used is MIT License.