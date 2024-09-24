# **Data Analysis Approach to Assisting a Client in Finding a Home in Chicago**
In my analysis of the Chicago housing dataset, I undertook a structured approach to assist a client in
finding suitable homes that meet their specific criteria. Here’s a breakdown of the process:
## **Importing Libraries:** 
I began by importing essential libraries, including pandas for data manipulation,
seaborn and matplotlib for visualization, and numpy for numerical operations.
## **Loading the Data:** 
The dataset, which contains 3,491 entries across 17 columns, was loaded from an
Excel file. This dataset includes critical information about various properties, such as price, location, and
features etc.
## **Data Exploration:** 
Initial exploration involved reviewing the first few rows of the dataset and gathering
basic information. I identified key features such as the number of bedrooms, bathrooms, and the
neighborhood name. This exploration phase highlighted that while most columns had complete data, the
`neighborhood_name` column had 24 missing entries.
## **Data Cleaning:** 
To address the missing values, I filled gaps in the `neighborhood_name` column with
'Unknown'. Additionally, I converted the `percentage_change` column to numeric format to facilitate
analysis.
## **Data Filtering:** 
To meet the client’s preferences, I set parameters based on a maximum price of $18,500,
a minimum of one bedroom, and focused on neighborhoods of interest, specifically Lincoln Park and
Lakeview. This filtering step resulted in a refined list of homes that aligned with the client’s budget and
location preferences.
# **Results:** 
The filtered results yielded several recommended homes, all located in Lincoln Park,
highlighting their respective prices, number of beds, and baths. This targeted approach ensured that the
client received relevant options that fit their criteria.
## **Recommendations:** 
The final output included a clear list of recommended homes, allowing the client to
make informed decisions based on their housing needs.
# **Conclusion**: 
By systematically exploring, cleaning, and analyzing the dataset, I effectively narrowed
down housing options tailored to the client's specifications. This method not only enhances the decisionmaking process but also provides the client with valuable insights into the Chicago housing market. The
results indicate a promising selection of properties that can serve as potential homes for the client.
