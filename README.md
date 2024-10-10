PROJECT: **Car Sales in Botswana and South Africa in 2022. Exploratory Data Analysis (EDA)**  

AUTHOR: **Darina Bunak**  

TECHNOLOGIES: **PowerBI (DAX)**  

##  
![Sales_01_overall](https://github.com/user-attachments/assets/1206a116-d450-468e-ad64-0812cdf59d7c)

##  
**DATASET**  

The spreadsheets used for this analysis imitate **sales data** for **Jan - Dec 2022** generated by **10 car dealers** operating in **Botswana and South Africa**.    
**Botswana** is presented by **7 dealers** located in **6 different cities**. **South Africa** is presented by **3 dealers** in **3 different cities**.   
The dataset consists of **3 tables** and provides the following parameters.  

  * **Dealers:** Dealer_ID, Dealer_Name, City, Country  
  * **Car_Models:** Model_ID, Brand, Segment, Engine_Size, Fuel, Price(USD), Profit(USD)  
  * **Sales:*** Date, Dealer_ID, Model_ID
    
*In addition, the following parameters were *calculated* for Sales table: *Sale_ID, Profit, Quantity, Revenue*
##  

**METRICS**  

The interactive dashboard reflects:
- [x] **Total revenue by country**  
- [x] **Top-3 most popular car models**  
- [x] **Revenue and profit generated by each car brand**  
- [x] **Geographical distribution of shops with their respective revenue and the number of cars sold**
- [x] **Highlights:** Overall Revenue, Overall Profit, Nr of Brands, Nr of Models, Nr of cars sold
##  

**OBSERVATIONS**  

**1.** The highlights show that **347 cars** were sold in total in 2022. That corresponds to **10 different car brands** and **15 different models** sold across 2 countries. The **overall revenue** generated by all 10 car dealers in the two countries was **$9 071 000**. The **profit** reached **$1 119 000**.  

**2.** Although by area, **Botswana** is about two times smaller than South Africa, in 2022, its car dealers **generated 67.42% ($6 116 000) of the overall revenue** for both countries. The **South Africa**'s dealers contributed only **32.58% ($2 955 000) of the overall revenue**. These numbers roughly coincide with the **number of car dealers in each country**: 7 in Botswana and 3 in South Africa.  

**3.** The bar chart representing **top-3 most popular models**, in fact, displays 4 model names, which **do not show significant difference in number of sales**. The most popular car model among customers in 2022 was 3 Series(BMW) with 33 sales in total. It was closely followed by Qashqai(Nissan) with 32 sales. The third place by popularity was, however, shared by Polo(Volkswagen) and Rio(Kia) sold 29 times each.  

**4.** In terms of **revenue generated by each of the 10 car brands**, the figures are spread across a wide spectrum, ranging **from $228 000** by Renault **to $1 785 000** by BMW. The **profit** line, in general, **follows the revenue** trend with **two exceptions: Toyota and Ford**. Those two brands returned **significantly higher profits with respect to their revenue** figures.

**5.** The interactive map shows **uneven geographical distribution of the car dealer shops**, which suggests logistical consequences. Only two of the sales points are located on the coast (South Africa: Durban, Cape Town), while the rest are situated inland. Botswana's shops are clustered around big cities and have shorter distances between each other, in comparison to the shops in South Africa.

**6.** Unsurprisingly, the **biggest revenue in each country was generated in capital cities**: $2 006 000 (77 cars) in Gaborone (Botswana) and $1 263 000 (46 cars) in Cape Town (South Africa).

![Sales_06_Map](https://github.com/user-attachments/assets/7bc217a6-32e8-4f06-885f-b399b710e07c)


##  

**INSIGHTS**  

Based on the OBSERVATIONS above, here are some points to consider further:
- **Is South Africa's demand covered** by the number of car dealers presented or **is the market undersaturated?** What is the **growth potential** there?
- **What is the average revenue by shop in each country?** In the capital? Outside of it? Which country/ location is more profitable?
- **What makes the most popular models win?** Do they represent the whole spectrum of segments? Do they have anything in common? If so, do they indicate certain preferences by customers (fuel type/ engine size/ insurance policy/ colour?)
- **Toyota and Ford are worth further investigation**. What is the key to their success, customers' trust and respect for the **brand or certain features** that they can be found in other cars? If customers trust the brands themselves, will it be justified to cut off the least profitable models and extend the representation of these two well-loved brands? If it is about features or feature/price ratio, there might be other cars fitting this golden ratio and representing them might show similar profitability in the future.
- **Is there competition between closely located shops in Botswana (e.g. in the capital region)?** If so, could it be eliminated by e.g. segment separation or model distribution? **Is the logistical model optimised?** Will it be cheaper if more shops open in South Africa? What would be the best location to open them, on the coast or inland?

![Sales_07_by brand](https://github.com/user-attachments/assets/0810efbe-cd38-4078-9bb9-41414609de69)
##  
