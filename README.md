# Sales-Analysis-for-a-Pizza-shop
The Project takes a deep analysis of the sales generated focusing on the KPIs , trend analysis, best and worst sellers, and gives recommendations on where to improve

# DASHBOARD
<img width="1907" height="1080" alt="image" src="https://github.com/user-attachments/assets/e0ea66c1-0e51-4778-b6a5-c20a8e810373" />


**THIS IS HOW I ARRIVED AT THE FIGURES ON THE DASHBOARD ABOVE USING POSTGRESQL**

**#THE KEY PERFORMANCE INDICATORS **

To arrive at this KPIs, I did the querying using PostgreSQL to act as my point of reference for accuracy nefore going ahead and working on the same in Power BI by creating measures to make visualization easy.
The KPIs include:

- Total Revenue
<img width="975" height="279" alt="image" src="https://github.com/user-attachments/assets/8913ca39-11d0-4a3c-8379-ce6377a13a98" />

**INSIGHT  GENERATED**

The total revenue generated for the year stood at $817,860. From the Analysis, the most vibrant days upon which majority of the sales hapen are betwwen Thursday and Saturday. This is showcased by the Daily trand bar chart, with Thursday showing 3239 sales, Friday showing 3538 sales, and Saturday showing 3158 sales. Additionally, the most vibrant times according to the Hourly trend are betwwen 12pm and 1pm and also between 5pm and 6pm.

**RECOMMENDATION**

Therefore, according to this insigths drawn, the business oughts to maximize the sales of these 3 days leading to the weekend, and also the most active times of the day to see maximum sales are made. However, we can introduce marketing and promotional activities for Sunday, Monday, and Tuesday since they show potential of breaching the 3000 sales mark.
  
- Average Order Value
<img width="975" height="186" alt="image" src="https://github.com/user-attachments/assets/f415a9e2-01b3-46ab-a6b1-174e6bc57614" />

  
- Total Pizzas Sold
<img width="975" height="238" alt="image" src="https://github.com/user-attachments/assets/35859697-eea0-439f-908d-6ee499b7b777" />

  
- Total Orders
<img width="975" height="197" alt="image" src="https://github.com/user-attachments/assets/cb80f8d9-ef8e-4773-ba4a-456834840ea5" />

  
- Average Pizzas per Order.
<img width="975" height="195" alt="image" src="https://github.com/user-attachments/assets/c361e9fb-a067-4538-a4db-245e1f216544" />

I went ahead to visualize the various aspects of the sales data that allowed us to gain valuable insights and understanding of the key trends from it. These are the various identified requirements that in the end aided in the creation of the sales dashboard.

1. Daily Trends for Total Orders
   
<img width="975" height="412" alt="image" src="https://github.com/user-attachments/assets/d6c8b5cd-d795-4938-bff5-ce092f2096d2" />

INSIGHT - Thursday, Friday, and Saturday shows that they are days where we receive maximum orders.

RECOMMENDATION - This high sales start as we head towards the weekend. As a business, we can recommend focusing on this days to ensure we get maximum orders, which will in the long-run, conribute towards growing our revenue.

<img width="562" height="239" alt="image" src="https://github.com/user-attachments/assets/1b9fa859-8486-4aea-b51c-18fe04236601" />

2. Hourly trend for Total Orders
   
<img width="975" height="245" alt="image" src="https://github.com/user-attachments/assets/62aff130-9084-45b1-b542-ac6fd55fa344" />

INSIGHT - The visualization below shows that from 9am and 10am, as well as late in the night at 11pm are the times where we make the least sales. However, the peak times of the day that we make most of our sales are between 12pm and 1pm, and between 5pm and 6pm. Therefore, we note that this may be because it is during lunch hour where people take beaks to get their lunches and also after working hours where people are getting to unwind from their day of work.
Therefore, we can maximize these two durations, probably instituting more serving spots to ensure that we seerve the maximum numbers at this times. Additionally, we can introduce a new pizza package, say, the Kingly category at this hour, market it for this specific hours and price it a bit higher, sowcase why it is priced so high. This will encourage people to want totaste it, or, it will make people decide to go for the second most affordable pizza, which in the long run, it is still a win for the house where we witness revenue surges at this duration.

<img width="644" height="238" alt="image" src="https://github.com/user-attachments/assets/39492166-2f74-4004-acd1-8e29c44eda37" />


3. Percentage of sales by Pizza Category
   
<img width="975" height="264" alt="image" src="https://github.com/user-attachments/assets/4c63b6d7-0e47-47ca-9145-7aef21fdcc6d" />

INSIGHT - The pie cart heps me to showcase the distribution of sales across various pizza categories.  It allowed me tp provide the insights necessary to determine the popularity of various pizza categories, and their ultimate contribution to the sales of the business. The CLASSIC category contributes the most revenue for our business.  The total pizzas sold has breached the 14000 sale mark, owever, it show potential for breaking the 15000 ceiling mark with some marketing. 
Additionally, the CLASSIC category  generates the highest sales, standing above the rest with a 26.91% contribution.

<img width="439" height="191" alt="image" src="https://github.com/user-attachments/assets/8ff40966-8171-471a-9845-0c3595658c25" />



4. Percentage of Sales by Pizza Size
5. 
<img width="975" height="419" alt="image" src="https://github.com/user-attachments/assets/aee82ca2-d9d5-44ec-b167-16e2ff4761a5" />

INSIGHT - This pie chart represents the percentage of sales connected to the various pizza sizes that our business sells.  It showcases the customer preferences of the sizes we sell. The pie chart shows that the majority of our customers prefers the LARGE pizza size, showing that we sold a whooping 45.89%

RECOMMENDATION - I can recommend directing our effort towards marketing our XXL and XL sizes to see their contribution to our sales also rise. Additonally, we can suspend the production of the XXL size and direct the effort more to ur best seller, the LARGE pizza th generate maximum sales revenue from it.

<img width="407" height="196" alt="image" src="https://github.com/user-attachments/assets/5024a47a-bb12-4019-a3a7-5a590097de05" />


6. Total Pizza Sold by Pizza Category
<img width="975" height="450" alt="image" src="https://github.com/user-attachments/assets/7bd69c2b-8a66-4f2a-b153-f65cb0f49d28" />

INSIGHT - The CLASSIC pizza category is our best revenue generator for the sales made. Standing at a total of 14888 sales made, it contributes 26.91% of our revenue.
RECOMMENDATION - CLASSIC category shows great potential of breaching the 15000 sales ceiing. Therefore, I recommend introducing some promotional targets for the next year that will help us get to this 15000 ceiling for this category.
Additionally, we can have the majority of our energy dierected from the CLASSIC to the other categories, for example, introducing vibrant marketing and promotions for the CHICKEN, VEGGIE, and SUPREME categories to ensure we draw maximu sales from the. We may set the target to being a 12000 ceiling mark for these categories and direct our efforts towards attaining this.

<img width="359" height="255" alt="image" src="https://github.com/user-attachments/assets/769be51f-249a-4782-b28f-95db2affaefd" />


8. The Top 5 and Bottom 5 sellers by pizzas sold
<img width="975" height="463" alt="image" src="https://github.com/user-attachments/assets/2fb915fb-23e4-4083-a639-3ab3e3d21050" />
<img width="975" height="463" alt="image" src="https://github.com/user-attachments/assets/05b6dd3d-765b-43cf-9c31-89e9601b6eb9" />


INSIGHTS - Our best selling pizza name is the Classic, then the berbecue, while the least selling pizza is the Brie followed by the Mediterrenean pizza.
<img width="847" height="195" alt="image" src="https://github.com/user-attachments/assets/5c1d9347-5bc0-4425-accb-ccd541140906" />




