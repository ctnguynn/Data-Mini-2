# Data-Mini-2
Welcome to Data Mini #2! You and your teammates will have from Friday, the 27th, at 5:30 pm to Sunday, the 1st, at 11:59 am to explore and submit a presentation about your data analysis. 

This Git repository contains this `README` file and the dataset in a `CSV` format. We recommend you use Duke's Container Manager to access your preferred IDE. 

## How to Participate
1. Fork the repository emailed to you by trisha.iyer@duke.edu 
2. Load the data from `For_Hire_Vehicles_(FHV)_-_Active_20260219.csv.zip`: Click on the file, click “View Raw”, and download. 
3. Come up with a question to answer with data analysis. Analyze the dataset and prepare a presentation of your findings.
4. Submit your files to your team’s Google Drive folder. Submission materials should include: your code notebook file, presentation media, citations to all outside resources, and a video file/link to the presentation.
Please do not attempt to push changes to this repository - it is read-only for participants.

## Data Dictionary
### For Hire Vehicles (FHV) - Active
#### About
The For Hire Vehicles (FHV) - Active dataset contains information on all TLC (Taxi and Limousine Commission) licensed for-hire vehicles in good standing. The dataset is maintained by NYC's Taxi and Limousine Commission and is updated daily between 4–7 PM. Each record represents an active for-hire vehicle operating under TLC authorization, with details about the vehicle, its owner, base information, and regulatory status. The dataset includes 104,000 records across 23 columns and reflects vehicle status as of the Last Date Updated and Last Time Updated fields.

Data Source: NYC Taxi and Limousine Commission (TLC)
Last Updated: February 25, 2026
Update Frequency: Daily
Link: https://data.cityofnewyork.us/Transportation/For-Hire-Vehicles-FHV-Active/8wbx-tsch/about_data 

#### Data Variables
Each row represents a single for-hire vehicle. The dataset includes vehicle identifiers, owner information, licensing details, vehicle specifications, base/company information, and regulatory dates.

| variable | data_type | description |
|----------|-----------|-------------|
| active_permit | text | Indicator showing whether the permit is active or inactive |
| vehicle_license_number | text | Unique FHV vehicle license number assigned by TLC |
| name | text | Name of the vehicle owner |
| license_type | text | Type of TLC license held by the for-hire vehicle |
| expiration_date | timestamp | Date when the vehicle's license expires |
| permit_license_number | text | Unique permit license number |
| dmv_license_plate_number | text | Vehicle's DMV-registered license plate number |
| vehicle_vin_number | text | Vehicle Identification Number (VIN) |
| wheelchair_accessible | text | Indicator for wheelchair accessibility of the vehicle |
| certification_date | timestamp | Date when the vehicle was certified |
| hack_up_date | timestamp | Date of the vehicle's hack-up (inspection/update) |
| vehicle_year | numeric | Year of the vehicle's manufacture |
| base_number | text | Unique identifier for the base/company operating the vehicle |
| base_name | text | Name of the base/company operating the vehicle |
| base_type | text | Classification of the base (e.g., individual, company) |
| veh | text | Hybrid vehicle indicator |
| base_telephone_number | text | Phone number for the base/company |
| website | text | Website URL for the base/company |
| base_address | text | Street address of the base/company |
| reason | text | Reason code for suspension or regulatory status (A, B, C, or G) |
| order_date | timestamp | Date when suspension was ordered (if applicable) |
| last_date_updated | timestamp | Last date the record was updated in the dataset |
| last_time_updated | text | Last time the record was updated in the dataset |

# Competition Policies
## Code of Conduct
### AI and Online Sources
* Analysis in this competition should reflect your own work; although we cannot prohibit AI, you should not depend on it in your analysis. Obvious or extreme usage of LLMs will be considered in judging.
* Your team must include citations for forums (Stack Overflow), textbooks, and other references
* You must provide a link to any AI chat conversations used
* You must list all citations (including the original study’s citation found at the bottom of this `README`) at the end of your code notebook. Failure in doing so will result in a large point deduction during judging.
* You may reuse code from your own research or class projects
* Citations should be listed in the code notebook file, presentation media, or a separate document.

## Analysis
* Must answer a question that your team chooses
* All types of data modeling are allowed
* All coding languages are allowed
* Your team may use the NYC Open Data visualization tool, but only for exploratory data analysis.

## Submission Requirements
* You and your team should submit the following to your Google Drive folder:
Your code notebook file (QMD, R script, Jupyter, etc.)
Presentation media (slides, PDF, link to an HTML, visualizations, etc)
Citations to all outside resources: please read the Code of Conduct for more information
A link to your forked GitHub repository
A video file/link to the presentation
* Video presentations may be recorded through Zoom, augmented videos, or in-person.
* You and your teammates will have received an email from susan.li@duke.edu near the beginning of the competition start
* Your team’s Google Drive folder contents will not be accessible to view, comment on, or edit by any other team.

## Judging
* Winners will be announced on Sunday, March 8th
* As stated earlier, you must come up with a question that your team will use to guide your statistical analysis. 
* A fair evaluation will be justified by multiple people deciding on competition winners.
* The judging criteria is as follows:
1) Communication: Clarity of presentation, logical structure, and ability to explain findings to a broad audience. - 20%
2) Creativity & Insight: Depth of analysis, creativity in approach, and ability to identify meaningful patterns. - 40%
3) Reproducibility: Well-organized code, clear documentation, and transparent workflows. - 5%
4) Visualization & Design: Effective use of charts and visuals to support your conclusions. - 25%
5) Technical Soundness: Appropriate use of statistical methods, reasonable assumptions, and valid interpretations. - 10%
* This will be prioritized more than the experience level of the statistical methods your team members used. This will account for differing experience levels across competitors

## Other Competitions from SSMU
1) Duke’s StatSci Majors Union will be hosting Data Mini #3 on Saturday, April 4th. This competition will be in a full-day format: teams will meet at 11 am in Wilkinson 126. Competitors will have until 4:30 pm to analyse and submit presentation materials, and presentations will occur live until 5:30 pm. Please contact Chelsea Nguyen (chelsea.nguyen@duke.edu) with any questions!
2) In addition, ASA DataFest 2026 at Duke, organized by the Department of Statistical Science, will take place in Perkins Library on Duke University West Campus, Friday, March 20, through Sunday, March 22. Similar to Data Minis, DataFest is a data analysis competition where teams of up to five students attack a large, complex, and surprise data set over a weekend. Please reach out to Dr. Alexander Fisher (alexander.fisher@duke.edu) with any questions.

## Dataset Acknowledgment
This project utilizes the For Hire Vehicles (FHV) - Active dataset, maintained and publicly released by New York City's Taxi and Limousine Commission (TLC) through NYC OpenData. The dataset contains comprehensive information on all TLC-licensed for-hire vehicles in good standing and is updated daily to ensure accuracy and currency. We are grateful to the TLC and NYC OpenData for making this valuable public resource freely available for research and analysis.

### Citation
New York City Taxi and Limousine Commission. (2026). For Hire Vehicles (FHV) - Active [Data set]. NYC OpenData. Retrieved from https://data.cityofnewyork.us/Transportation/For-Hire-Vehicles-FHV-Active/8wbx-tsch/about_data 
This citation must be included at the end of your code notebook.

## About This Event
Data Mini #2 was organized by Duke's Statistical Science Majors Union - Competitions and Opportunities Committee. Contributing members of the committee and the SSMU executive team are listed below:
* Hanna Chee, ‘29
* Trisha Iyer, ‘28
* Hyunjin Lee, ‘27
* Susan Li, ‘29
* Liane Ma, ‘27
* Chelsea Nguyen, ‘28
* Cooper Ruffing, ‘27
* Derek Wang, ‘28
* Amy Xu, ‘27
* Allison Yang, ‘27
* And an additional thank-you goes out to the professors who helped advertise the event.
