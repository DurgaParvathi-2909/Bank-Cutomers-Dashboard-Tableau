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
The pie chart reveals which regions hold the highest and lowest total balances. This helps identify regions with the most financial activity.

𝐆𝐞𝐧𝐝𝐞𝐫 𝐃𝐢𝐬𝐭𝐫𝐢𝐛𝐮𝐭𝐢𝐨𝐧:
The bar chart shows the number of male and female customers. Color-coded bars provide a clear visual distinction between genders.

𝐉𝐨𝐛 𝐂𝐥𝐚𝐬𝐬 𝐁𝐚𝐥𝐚𝐧𝐜𝐞 𝐛𝐲 𝐑𝐞𝐠𝐢𝐨𝐧:
The graph identifies which job classifications contribute the most and least to the balance in each region. This can highlight financial contributions based on job roles.

𝐀𝐯𝐞𝐫𝐚𝐠𝐞 𝐁𝐚𝐥𝐚𝐧𝐜𝐞 𝐛𝐲 𝐆𝐞𝐧𝐝𝐞𝐫:
The table shows average balances for male and female customers. It helps in understanding gender-based financial behaviors.

𝐀𝐠𝐞 𝐯𝐬. 𝐁𝐚𝐥𝐚𝐧𝐜𝐞:
The scatter plot reveals any correlation between age and balance. Different shapes and colors provide additional insights into job classifications and gender distribution.

# Recommendations
𝐅𝐮𝐫𝐭𝐡𝐞𝐫 𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬:
Consider exploring trends over time by analyzing the Date Joined field. This could uncover seasonal patterns or changes in customer behavior.

𝐒𝐞𝐠𝐦𝐞𝐧𝐭 𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬:
Perform segmentation analysis to identify high-value customer profiles based on balance, age, and job classification.

𝐀𝐝𝐝𝐢𝐭𝐢𝐨𝐧𝐚𝐥 𝐕𝐢𝐬𝐮𝐚𝐥𝐢𝐳𝐚𝐭𝐢𝐨𝐧𝐬:
Add trend lines or regression analysis to the scatter plot to better understand the relationship between age and balance.

𝐄𝐧𝐡𝐚𝐧𝐜𝐞𝐝 𝐈𝐧𝐭𝐞𝐫𝐚𝐜𝐭𝐢𝐯𝐢𝐭𝐲:
Implement filters and drill-down options to allow users to explore specific regions, job classifications, or age groups in more detail.


𝑇ℎ𝑖𝑠 𝑝𝑟𝑜𝑗𝑒𝑐𝑡 𝑎𝑖𝑚𝑒𝑑 𝑡𝑜 𝑒𝑥𝑝𝑙𝑜𝑟𝑒 𝑎𝑛𝑑 𝑣𝑖𝑠𝑢𝑎𝑙𝑖𝑧𝑒 𝑘𝑒𝑦 𝑎𝑠𝑝𝑒𝑐𝑡𝑠 𝑜𝑓 𝑡ℎ𝑒 𝑏𝑎𝑛𝑘'𝑠 𝑐𝑢𝑠𝑡𝑜𝑚𝑒𝑟 𝑑𝑎𝑡𝑎𝑠𝑒𝑡 𝑡𝑜 𝑔𝑎𝑖𝑛 𝑖𝑛𝑠𝑖𝑔ℎ𝑡𝑠 𝑖𝑛𝑡𝑜 𝑐𝑢𝑠𝑡𝑜𝑚𝑒𝑟 𝑑𝑒𝑚𝑜𝑔𝑟𝑎𝑝ℎ𝑖𝑐𝑠, 𝑓𝑖𝑛𝑎𝑛𝑐𝑖𝑎𝑙 𝑏𝑒ℎ𝑎𝑣𝑖𝑜𝑟, 𝑎𝑛𝑑 𝑟𝑒𝑔𝑖𝑜𝑛𝑎𝑙 𝑑𝑖𝑠𝑡𝑟𝑖𝑏𝑢𝑡𝑖𝑜𝑛. 𝑇ℎ𝑒 𝑣𝑖𝑠𝑢𝑎𝑙𝑖𝑧𝑎𝑡𝑖𝑜𝑛𝑠 ℎ𝑒𝑙𝑝 𝑖𝑛 𝑢𝑛𝑑𝑒𝑟𝑠𝑡𝑎𝑛𝑑𝑖𝑛𝑔 𝑡ℎ𝑒 𝑑𝑖𝑠𝑡𝑟𝑖𝑏𝑢𝑡𝑖𝑜𝑛 𝑜𝑓 𝑎𝑐𝑐𝑜𝑢𝑛𝑡 𝑏𝑎𝑙𝑎𝑛𝑐𝑒𝑠, 𝑐𝑢𝑠𝑡𝑜𝑚𝑒𝑟 𝑑𝑒𝑚𝑜𝑔𝑟𝑎𝑝ℎ𝑖𝑐𝑠 𝑏𝑦 𝑔𝑒𝑛𝑑𝑒𝑟, 𝑗𝑜𝑏 𝑐𝑙𝑎𝑠𝑠 𝑝𝑒𝑟𝑓𝑜𝑟𝑚𝑎𝑛𝑐𝑒 𝑎𝑐𝑟𝑜𝑠𝑠 𝑟𝑒𝑔𝑖𝑜𝑛𝑠, 𝑎𝑣𝑒𝑟𝑎𝑔𝑒 𝑏𝑎𝑙𝑎𝑛𝑐𝑒𝑠 𝑏𝑦 𝑔𝑒𝑛𝑑𝑒𝑟, 𝑎𝑛𝑑 𝑡ℎ𝑒 𝑟𝑒𝑙𝑎𝑡𝑖𝑜𝑛𝑠ℎ𝑖𝑝 𝑏𝑒𝑡𝑤𝑒𝑒𝑛 𝑎𝑔𝑒 𝑎𝑛𝑑 𝑏𝑎𝑙𝑎𝑛𝑐𝑒.

# Live Dashboard Access
https://public.tableau.com/app/profile/bessetty.durga.parvathi/viz/Practiceset-3Bank-CustomersDataset_17232876747380/CustomerAgeandBalanceScatterAnalysis?publish=yes


# Snapshot of Bank Customers Dashboard (Tableau Public)
![Bank Customers Dashboard-Tableau](https://github.com/user-attachments/assets/f2d2239a-5219-453c-b2ac-8efc693f8ab0)



