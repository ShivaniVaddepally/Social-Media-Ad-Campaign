# Social-Media-Ad-Campaign

![image](https://github.com/user-attachments/assets/864e903e-f5ec-47f7-a64d-bd37b7334dec)


About the Dataset:
Link- https://www.kaggle.com/datasets/loveall/clicks-conversion-tracking

The data set is retrieved from the Kaggle data set Sales Conversion Optimization by GOKAGGLERS, where it describes the marketing and conversion information of an anonymous organisation’s social media ad campaign.

Overall, the data has 1143 entries and 11 columns. A brief description for each column can be given as follows:

ad_id: a unique ID for each ad.
xyzcampaignid: an ID associated with each ad campaign of XYZ company.
fbcampaignid: an ID associated with how Facebook tracks each campaign.
age: age of the person to whom the ad is shown.
gender: gender of the person to whom the add is shown
interest: a code specifying the category to which the person’s interest belongs (interests are as mentioned in the person’s Facebook public profile).
Impressions: the number of times the ad was shown.
Clicks: number of clicks on for that ad.
Spent: Amount paid by company xyz to Facebook, to show that ad.
Total conversion: Total number of people who enquired about the product after seeing the ad.
Approved conversion: Total number of people who bought the product after seeing the ad.
Data Cleaning & Analysis - Microsoft Excel

Data Visualization - Microsoft PowerBI

Methodology:
After observation, it was found that there were no null or invalid type values present in the data. However, it was easy to notice that some entries (204 entries) were having error as Column “Clicks” had value 0 but Column “Total_Conversion” had non-zero values. This is illogical because an ad cannot still gain postive conversions (customers) while no one clicks on it. So, after removing those data, Our dataset consist a total of 939 entries.

Feature Engineering

Using the features given in the data set, we can also perform feature engineering to generate some KPIs that are important for later analysis:

CPM (Cost per Mille): It is a metric that represents the cost of displaying an ad to 1,000 people. In other words, it measures how much a business pays for every 1,000 ad impressions.
Cost per click (CPC): It is a metric that represents the cost of getting a user to click on an ad. It measures how much a business pays for every click on their ad.
Click-through rate (CTR): It is a metric that represents the percentage of users who click on an ad after seeing it. It measures the effectiveness of an ad in getting users to click through to a website or landing page.
CPA (Cost per Acquisition/Action): It is a metric that represents the cost of acquiring a new customer through an ad campaign. It measures how much a business pays for every new customer acquired through their ad.
