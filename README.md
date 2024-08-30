# Data Analyst

### Technical Skills: 
SQL, Python, Snowflake, Power BI, Excel, AWS, S3, Jupyter Notebooks, Apache Zeppelin

## Education
- M.S., Library & Information Science | North Carolina Central University (_May 2020_)
- B.S., Education | Appalachian State University (_May 2014_)

## Work Experience
#### Merchandising Data Analyst @ Advance Auto Parts 

In my current role, I focus on leveraging data analysis to drive product assortment strategies and business optimization. I analyze and mine data using statistical methods to identify patterns and insights related to our product assortment. My responsibilities include communicating and collaborating cross-functionally with team members to pinpoint and address business issues. I develop strong partnerships with business management teams and actively participate in meetings to measure and optimize the effectiveness of our product assortment.

I handle data preparation and cleaning using Python, SQL, and Excel, which enables me to automate routine tasks and optimize reports. Additionally, I create interactive PowerBI reports by using storytelling features such as drill through filters, bookmarks, themes, and selection panes, allowing business users to gather data insights quickly and ensuring that analytical findings and assortment recommendations are presented clearly and concisely to key stakeholders. My technical skills in SQL, Python, and Microsoft Power BI, combined with my proficiency in data analysis and effective communication, allow me to drive actionable insights and enhance decision-making processes.

#### Media Data Specialist @ Wake County Public School System

As a Media Data Specialist, I specialized in transforming raw data into actionable insights to drive strategic decision-making and enhance user experience. I analyzed regular data from internal reports, focusing on technology item status, usage, assortment, and budget management. Leveraging my expertise in SQL and Microsoft Excel, I compiled detailed reports and created dynamic dashboards using Tableau to inform stakeholders and guide strategic planning. My work included developing reports that supported the optimization of resources, crafting annual budgets, and making data-driven decisions on inventory and user accounts. With strong interpersonal skills, effective communication, and problem-solving abilities, I was dedicated to using data analytics to improve processes and drive continuous improvement.

## A Few Projects: 
### Stocking Location Recommendations: 
[Query Example](https://github.com/ashleigh7623/ashleigh.duffy/blob/be195e78c28ae1ae855134f3f8c42cdae4097a00/assets/projects/stocking_example_segment)

In this project, I provided data-driven recommendations to optimize product stocking locations across the supply chain. The objective was to ensure that products didn't remain unsold on shelves too long, thereby avoiding financial losses and improving inventory management.
The project enhanced the company's ability to allocate products efficiently and prioritize inventory investments.
#### Key Steps Taken:
   - Cleaned and conducted analysis in SQL on datasets containing up to millions of records from various sources to determine which key metrics would decide the best location for each product, including moving items between the factory, warehouse, and stores.
   - Initiated meetings to discuss how the outcome of these recommendations would effect other teams.
   - Automated data processing and recommendations using Python, which involved looping through product names and life cycles, and exporting results into organized Excel files using Openpyxl, summarizing feedback on recommendations and refining data accordingly.
   - Created a PPT and meeting to teach-out the "rules"/filters used to categorize each product into their recommended location and directions on processing the results. 
   - Developed a Power BI report to visualize acceptance rates and statistics, aiding leadership in making informed business decisions.

#### Recommendations & Next Steps
- When completed quarterly, one can track the performance of investments and the amount of inventory being introduced into the supply chain.
- Helps create a system to check obsolete inventory and move it to the end of it's shipping location lifecycle (from store to factory) on a regular cadence.

### Coverage Report Analysis:
The primary goal of this project is to create a comprehensive Coverage Report that evaluates the availability of parts in relation to vehicles identified as "VIO" (Vehicles in Operation). The analysis will determine whether the necessary SKUs are present in our catalog and assess the coverage gaps based on their regional distribution and stocking location.

#### Key Steps Taken:
1. **Catalog Verification**:
   - **Check SKU Availability**: Determine if the SKUs for the VIO vehicles are present in our catalog. For each vehicle, identify if its corresponding part is listed as available and determine if it is an existing part for that vehicle.
   - **Identify Catalog Gaps**: Highlight which parts we have SKUs that are missing from the catalog entirely, indicating a lack of parts for certain vehicles.

2. **Coverage Analysis**:
   - **Percentage of Coverage**: Calculate the percentage of SKUs available for each vehicle model down to it's specific fuel. This will help in understanding the extent of our coverage.
   - **Regional Distribution**: Analyze the geographic distribution of SKUs in relation to VIO. Identify if certain parts are available only in specific regions or stores, which may indicate potential coverage gaps or missed opportunities.

3. **Gap Assessment**:
   - **No SKU Availability**: Flag vehicles for which no SKU exists in our catalog.
   - **Limited Regional Coverage**: Identify situations where SKUs are available but limited to only one store or region, which could affect overall coverage and availability.
   - 
#### Recommendations & Next Steps
- This report will help in identifying areas where we may be missing out on potential sales and ensure that our catalog is adequately stocked to meet the needs of our VIO vehicles.
- Are we stocking this part in the area showing a high VIO? Are we overstocking a SKU or part in an area that has a low VIO? Do we even have a SKU in our catalog that fits this part?

##### Example of POWER BI Report:
- **Coverage Report**: A detailed report showing whether we have the necessary SKUs for VIO vehicles, including:
  - A list of missing SKUs.
  - The percentage of available SKUs for each vehicle.
  - A breakdown of SKU availability by region or store.

