# Data-Cleaning-on-GoogleSheet-Excel
This dirty data was obtained from Kaggle. It contains sales record of different confectionaries, their cost, date of purchase, purchase ID, among other necessary details. This data is beginner-friendly and useful in practising your data analysis skills after a long time.
## Project Overview
Through the analysis of this data, insights are provided to the store owner regarding purchasing power, sales, and the best business days and months, as determined by the revenue generated and the number of items sold. While working on this data, I ensured that the purpose of the analysis was fully observed and executed.

### Data Source
The data was readily available on Kaggle by Ahmed Mohamed with the title: Cafe Sales - Dirty Data for Cleaning Training <https://www.kaggle.com/datasets/ahmedmohamed2003/cafe-sales-dirty-data-for-cleaning-training>

### Tools
- Excel & Google Sheet for data cleaning and visualisation

### Data Preparation
In the initial data preparation phase, I downloaded the dataset from Kaggle and then uploaded it to Microsoft Excel, where I sorted it to identify missing values and outliers. I first selected the entire sheet (Ctrl+A), then proceeded to filter.
The filter button made it easy to find UKNOWN, ERRORS and BLANKS.

 ### Before filter and sort:
 <img width="1014" height="874" alt="Screenshot 2025-08-25 121037" src="https://github.com/user-attachments/assets/73cf8b39-1d49-48b0-bf38-5af34c3d64aa" />

------

<img width="1066" height="940" alt="Screenshot 2025-08-25 121114" src="https://github.com/user-attachments/assets/87cfe19b-3bc9-42aa-af58-d05664615d42" />


#### Figure 1: image of raw data from Kaggle after upload to Excel




### After filter and sort:

- On Excel:
  
<img width="1356" height="980" alt="Screenshot 2025-08-25 120855" src="https://github.com/user-attachments/assets/23a7a886-9e2d-4160-ad72-7fe9d132b134" />


#### Figure 3: The image above is the image of raw data after partial cleaning on Excel


- On Google Sheet: 

<img width="1358" height="998" alt="Screenshot 2025-08-25 121248" src="https://github.com/user-attachments/assets/8c46fc06-6b2b-469c-b969-00f4e6e4da7d" />

#### Figure 3b: above is the image of raw data after complete cleaning, filtering and sorting on Google Sheet

After each row is cleaned, missing values are properly filled, I copied the downloaded data from Excel and uploaded it to a Google sheet, which I find to be more user-friendly. On the sheet, I split the date into day of the week, month, and year, as shown in the image above. Then I created pivot table(s) to derive insights into the data. 

### Exploratory Data Analysis
The Exploratory Data Analysis involves asking questions about the data that meet specific conditions, such as:
- The total amount spent on specific confectionery (the most sold confectionery)
- Total quantity sold
- Month with the highest quantity sold.

   - The most demanded item based on quantity: Coffee, with a total of 3878 sold in the year 2023
   - The least demanded item based on quantity: Smoothie, with a total of 3585 sold in the year 2023

   - Item that generated the most revenue: Salad. Amount generated **19075**. Sales Price: 5
   - Item that generated the least revenue: Cookie. Amount generated **3585**.  Sales Price: 1


<img width="596" height="256" alt="Screenshot 2025-08-27 165832" src="https://github.com/user-attachments/assets/5a42663b-b6c7-411c-b70f-10e5c9667ef0" />


#### Figure 4

Number of times customers came back for specific items can be seen below. The highest is Coffee, and the least is Smoothie.


<img width="608" height="348" alt="Screenshot 2025-08-25 124539" src="https://github.com/user-attachments/assets/33945406-c665-46e2-a8c1-4b999c28e7cb" />

#### Figure 5

The day of the week with the most sold items and revenue can be seen below. In this section, you can see that there is ERROR, UNKNOWN and BLANK. I did not remove these items as they could be valuable to the data.


<img width="431" height="248" alt="Screenshot 2025-08-25 124619" src="https://github.com/user-attachments/assets/e71161bb-09b2-4356-871d-f535880c1b61" />

#### Figure 6

### Data Analysis
Below are the results visualised: 

<img width="480" height="323" alt="Screenshot 2025-08-27 164723" src="https://github.com/user-attachments/assets/1ec06def-c0ff-459a-a552-076a6cba0135" />

------
<img width="499" height="338" alt="Screenshot 2025-08-27 164754" src="https://github.com/user-attachments/assets/2ae2fc8a-35dd-41f4-99ca-11a319e61c8d" />
