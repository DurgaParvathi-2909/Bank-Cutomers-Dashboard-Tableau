# Bank-Customers Dashboard | Tableau

# Problem Statement
The goal of this project is to explore the provided Bank Customers dataset to create interactive visualizations that offer insights into various aspects of customer data. The visualizations will help in understanding the distribution of balances across regions, customer demographics by gender, job class performance, average balances by gender, and the relationship between age and balance.

# Dataset Overview
𝐂𝐮𝐬𝐭𝐨𝐦𝐞𝐫 𝐈𝐃: Unique identifier for each customer.

𝐆𝐞𝐧𝐝𝐞𝐫: Gender of the customer (Male or Female).

𝐀𝐠𝐞: Age of the customer in years.

𝐑𝐞𝐠𝐢𝐨𝐧: Geographic region (East, West, North, South).

𝐉𝐨𝐛 𝐂𝐥𝐚𝐬𝐬𝐢𝐟𝐢𝐜𝐚𝐭𝐢𝐨𝐧: Type of job (Service, Business, Other).

𝐃𝐚𝐭𝐞 𝐉𝐨𝐢𝐧𝐞𝐝: Date the customer joined the bank.

𝐁𝐚𝐥𝐚𝐧𝐜𝐞: Customer's account balance

# Steps Followed
𝐋𝐨𝐚𝐝𝐞𝐝 𝐭𝐡𝐞 𝐃𝐚𝐭𝐚𝐬𝐞𝐭: Imported the Bank Customers dataset into Tableau.

𝐄𝐱𝐩𝐥𝐨𝐫𝐞𝐝 𝐃𝐚𝐭𝐚 𝐅𝐢𝐞𝐥𝐝𝐬: Familiarized with fields such as Customer ID, Gender, Age, Region, Job Classification, Date Joined, and Balance.

𝐃𝐚𝐭𝐚 𝐂𝐥𝐞𝐚𝐧𝐢𝐧𝐠: Ensured that the data was clean and well-formatted, with no missing values or inconsistencies.
Visualization Creation:

𝐏𝐢𝐞 𝐂𝐡𝐚𝐫𝐭 𝐟𝐨𝐫 𝐑𝐞𝐠𝐢𝐨𝐧𝐚𝐥 𝐁𝐚𝐥𝐚𝐧𝐜𝐞 𝐃𝐢𝐬𝐭𝐫𝐢𝐛𝐮𝐭𝐢𝐨𝐧:
Created a pie chart to show the total balance in each region (East, West, North, South).
Displayed the percentage of the total balance for each region using the Percent of Total calculation.

![Percentage of total balance in each region](https://github.com/user-attachments/assets/253c5d54-ee39-4d4d-b5ba-fe0408f48331)


𝐁𝐚𝐫 𝐂𝐡𝐚𝐫𝐭 𝐟𝐨𝐫 𝐂𝐮𝐬𝐭𝐨𝐦𝐞𝐫 𝐃𝐢𝐬𝐭𝐫𝐢𝐛𝐮𝐭𝐢𝐨𝐧 𝐛𝐲 𝐆𝐞𝐧𝐝𝐞𝐫:
Built a bar chart to show the number of customers by gender.
Added colors (Red for Female, Green for Male) and labels to display the distinct count of male and female customers.

![Gender Distribution](https://github.com/user-attachments/assets/5ebfad08-d4a4-46ee-824e-a2b0bc945268)


𝐆𝐫𝐚𝐩𝐡 𝐟𝐨𝐫 𝐉𝐨𝐛 𝐂𝐥𝐚𝐬𝐬 𝐚𝐧𝐝 𝐁𝐚𝐥𝐚𝐧𝐜𝐞 𝐛𝐲 𝐑𝐞𝐠𝐢𝐨𝐧:
Created a graph to show which job class has the highest and lowest sum of balance in each region.
Displayed both maximum and minimum balance values for each region.
![Job Classification and Balance by Region](https://github.com/user-attachments/assets/46ebbe11-def0-46ee-aa22-c5cbbd3cdbda)


𝐓𝐚𝐛𝐥𝐞 𝐟𝐨𝐫 𝐀𝐯𝐞𝐫𝐚𝐠𝐞 𝐁𝐚𝐥𝐚𝐧𝐜𝐞 𝐛𝐲 𝐆𝐞𝐧𝐝𝐞𝐫:
Used a calculated field to determine the average balance for male and female customers.
Presented the results in a table format with columns for Gender and Average Balance.
![Table for average balance by gender](https://github.com/user-attachments/assets/5ccc6017-5514-4bf8-8223-1c413235eb57)


𝐒𝐜𝐚𝐭𝐭𝐞𝐫 𝐏𝐥𝐨𝐭 𝐟𝐨𝐫 𝐀𝐠𝐞 𝐯𝐬. 𝐁𝐚𝐥𝐚𝐧𝐜𝐞:
Created a scatter plot with Age on the x-axis and Balance on the y-axis.
Used shapes to represent different job classifications and colored the data points based on gender.
![Customer Age and Balance Scatter Analysis](https://github.com/user-attachments/assets/9a51282a-5216-4638-a99d-d668d40cc3c1)

# Insights
𝐑𝐞𝐠𝐢𝐨𝐧𝐚𝐥 𝐁𝐚𝐥𝐚𝐧𝐜𝐞 𝐃𝐢𝐬𝐭𝐫𝐢𝐛𝐮𝐭𝐢𝐨𝐧:
The East region holds the highest total balance with 50.33% of the total, amounting to $30,451,829. This indicates a significant concentration of wealth in this region.
The South region follows with 27.05% and a total balance of $16,272,756, while the West and North regions account for 15.26% and 7.37% respectively, highlighting a disparity in balance distribution among regions.

𝐂𝐮𝐬𝐭𝐨𝐦𝐞𝐫 𝐀𝐠𝐞 𝐚𝐧𝐝 𝐁𝐚𝐥𝐚𝐧𝐜𝐞 𝐂𝐨𝐫𝐫𝐞𝐥𝐚𝐭𝐢𝐨𝐧:
The scatter plot of customer age against balance shows a broad distribution, with a higher density of customers aged 30-50 having balances ranging from 0 to $150K.
There is no clear linear relationship between age and balance, indicating that age alone is not a strong predictor of balance amount.

𝐉𝐨𝐛 𝐂𝐥𝐚𝐬𝐬𝐢𝐟𝐢𝐜𝐚𝐭𝐢𝐨𝐧 𝐚𝐧𝐝 𝐁𝐚𝐥𝐚𝐧𝐜𝐞 𝐛𝐲 𝐑𝐞𝐠𝐢𝐨𝐧:
The Service sector in the East region shows the highest balance at $25,937,116, suggesting a high concentration of wealth in this job classification and region.
Other job classifications and regions show significantly lower balances, indicating potential areas for growth or targeted marketing.

𝐆𝐞𝐧𝐝𝐞𝐫 𝐃𝐢𝐬𝐭𝐫𝐢𝐛𝐮𝐭𝐢𝐨𝐧:
Males constitute a higher customer count at 849 compared to females at 702. However, the average balance for both genders is relatively close, with males slightly higher ($39,737) than females ($38,229).
This suggests a fairly balanced financial behavior across genders, with a slightly higher male dominance in customer count.

# Recommendations

𝐓𝐚𝐫𝐠𝐞𝐭𝐞𝐝 𝐌𝐚𝐫𝐤𝐞𝐭𝐢𝐧𝐠 𝐚𝐧𝐝 𝐒𝐞𝐫𝐯𝐢𝐜𝐞𝐬:
Focus marketing and service offerings in the East region, especially in the Service sector, to leverage the high balance concentration.
Develop targeted financial products or incentives for the North region to boost its relatively lower balance share.

𝐀𝐠𝐞-𝐁𝐚𝐬𝐞𝐝 𝐅𝐢𝐧𝐚𝐧𝐜𝐢𝐚𝐥 𝐏𝐫𝐨𝐝𝐮𝐜𝐭𝐬:
Since customers aged 30-50 have a significant presence, consider designing age-specific financial products or investment options to cater to this demographic.
Promote educational resources or advisory services for younger customers to build early financial engagement.

𝐆𝐞𝐧𝐝𝐞𝐫-𝐅𝐨𝐜𝐮𝐬𝐞𝐝 𝐒𝐭𝐫𝐚𝐭𝐞𝐠𝐢𝐞𝐬:
Implement gender-inclusive marketing strategies and create products that address the needs of both male and female customers, ensuring equitable financial growth opportunities.
Conduct surveys or studies to understand the preferences of the female customer base better and tailor products to encourage higher participation.

𝐄𝐱𝐩𝐚𝐧𝐝 𝐁𝐮𝐬𝐢𝐧𝐞𝐬𝐬 𝐒𝐞𝐫𝐯𝐢𝐜𝐞𝐬:
Given the high balance in the Service sector, explore opportunities to expand business-related services or investments to further capitalize on this segment's potential.
Consider partnerships or collaborations with service-oriented businesses in the East region to attract more customers and increase balances.

𝑇ℎ𝑖𝑠 𝑝𝑟𝑜𝑗𝑒𝑐𝑡 𝑎𝑖𝑚𝑒𝑑 𝑡𝑜 𝑒𝑥𝑝𝑙𝑜𝑟𝑒 𝑎𝑛𝑑 𝑣𝑖𝑠𝑢𝑎𝑙𝑖𝑧𝑒 𝑘𝑒𝑦 𝑎𝑠𝑝𝑒𝑐𝑡𝑠 𝑜𝑓 𝑡ℎ𝑒 𝑏𝑎𝑛𝑘'𝑠 𝑐𝑢𝑠𝑡𝑜𝑚𝑒𝑟 𝑑𝑎𝑡𝑎𝑠𝑒𝑡 𝑡𝑜 𝑔𝑎𝑖𝑛 𝑖𝑛𝑠𝑖𝑔ℎ𝑡𝑠 𝑖𝑛𝑡𝑜 𝑐𝑢𝑠𝑡𝑜𝑚𝑒𝑟 𝑑𝑒𝑚𝑜𝑔𝑟𝑎𝑝ℎ𝑖𝑐𝑠, 𝑓𝑖𝑛𝑎𝑛𝑐𝑖𝑎𝑙 𝑏𝑒ℎ𝑎𝑣𝑖𝑜𝑟, 𝑎𝑛𝑑 𝑟𝑒𝑔𝑖𝑜𝑛𝑎𝑙 𝑑𝑖𝑠𝑡𝑟𝑖𝑏𝑢𝑡𝑖𝑜𝑛. 𝑇ℎ𝑒 𝑣𝑖𝑠𝑢𝑎𝑙𝑖𝑧𝑎𝑡𝑖𝑜𝑛𝑠 ℎ𝑒𝑙𝑝 𝑖𝑛 𝑢𝑛𝑑𝑒𝑟𝑠𝑡𝑎𝑛𝑑𝑖𝑛𝑔 𝑡ℎ𝑒 𝑑𝑖𝑠𝑡𝑟𝑖𝑏𝑢𝑡𝑖𝑜𝑛 𝑜𝑓 𝑎𝑐𝑐𝑜𝑢𝑛𝑡 𝑏𝑎𝑙𝑎𝑛𝑐𝑒𝑠, 𝑐𝑢𝑠𝑡𝑜𝑚𝑒𝑟 𝑑𝑒𝑚𝑜𝑔𝑟𝑎𝑝ℎ𝑖𝑐𝑠 𝑏𝑦 𝑔𝑒𝑛𝑑𝑒𝑟, 𝑗𝑜𝑏 𝑐𝑙𝑎𝑠𝑠 𝑝𝑒𝑟𝑓𝑜𝑟𝑚𝑎𝑛𝑐𝑒 𝑎𝑐𝑟𝑜𝑠𝑠 𝑟𝑒𝑔𝑖𝑜𝑛𝑠, 𝑎𝑣𝑒𝑟𝑎𝑔𝑒 𝑏𝑎𝑙𝑎𝑛𝑐𝑒𝑠 𝑏𝑦 𝑔𝑒𝑛𝑑𝑒𝑟, 𝑎𝑛𝑑 𝑡ℎ𝑒 𝑟𝑒𝑙𝑎𝑡𝑖𝑜𝑛𝑠ℎ𝑖𝑝 𝑏𝑒𝑡𝑤𝑒𝑒𝑛 𝑎𝑔𝑒 𝑎𝑛𝑑 𝑏𝑎𝑙𝑎𝑛𝑐𝑒.

# Live Dashboard Access
https://public.tableau.com/app/profile/bessetty.durga.parvathi/viz/Practiceset-3Bank-CustomersDataset_17232876747380/CustomerAgeandBalanceScatterAnalysis?publish=yes


# Snapshot of Bank Customers Dashboard (Tableau Public)
![Bank Customers Dashboard-Tableau](https://github.com/user-attachments/assets/f2d2239a-5219-453c-b2ac-8efc693f8ab0)



