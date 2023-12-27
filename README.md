# Facebook Ads Performance Dashboard

## Overview

This project aims to create a tactical dashboard for the Marketing department of a flower shop. In real-world scenarios, the data for the Marketing department usually originates from various sources. However, for the scope of this project, our focus is specifically on extracting and visualizing data from Facebook ads.

The primary objective of this project is to develop **a tactical dashboard** that empowers stakeholders to efficiently analyze and monitor marketing activities over time. The dashboard will facilitate zooming in and out on key metrics, allowing stakeholders to swiftly grasp trends and optimize Facebook ads campaigns.

By concentrating on data derived solely from Facebook ads, the dashboard provides a comprehensive and accessible tool for stakeholders to gain insights, make informed decisions, and enhance the overall effectiveness of their marketing strategies.

This project was built on Google Sheet. You can access the result file directly [here](https://docs.google.com/spreadsheets/d/16KZeQGB8j9_5bZ_J-d5jBx5klns38b09yr9ky-hDn2c/edit?usp=sharing).

## Preparing for Dashboard Creation

### 1. Defining dashboard type
The chosen dashboard type for this project is a Tactical Dashboard. Tactical dashboards are instrumental in the analysis and monitoring of processes, with a focus on mid-level management. The scope of this dashboard is tailored to the Marketing department, specifically for the management of Facebook ads.

### 2. Stakeholder requirements 

5W1H:
- **What:** They want to scale up performance while ensuring sustainability.
- **Who:** Digital Marketing Leader.
- **Why:** To achieve quick and effective results in paid marketing while managing costs.
- **When:** Optimization on a daily, weekly, and monthly basis.
- **Where:** Facebook Ads platform.
- **How:** Stakeholders have specific targets to optimize. Optimization involves learning from successful and unsuccessful ads, considering factors such as product, campaign, location, and time frames (daily, weekly, monthly).

### 3. Layers of dashboard

- Most noteworthy information:
   - Cost
   - Number of Messages
   - Cost per Message

- Important information:
   - Ad performance metrics:
     - Reach
     - Impressions
     - Frequency
   - Interaction metrics:
     - Clicks on the chat button
     - Click-through rate

- Detailed Information:
   - Location-based metrics
   - Product-based metrics
   - Time-based metrics

## Data Dictionary

| Column              | Description                                           |
|---------------------|-------------------------------------------------------|
| Reporting starts    | Date of the report                                    |
| Campaign name       | Name of the campaign                                  |
| Ad Set Name         | Subset within a campaign                              |
| Ad name             | Individual ad within an ad set                         |
| Objective           | Campaign objective                                    |
| Reach               | Number of people reached                              |
| Impressions         | Number of ad views                                     |
| Frequency           | Impressions per unique viewer (Frequency = Impressions/Reach) |
| Amount spent (VND)  | Total expenditure in Vietnamese Dong                   |
| CTR                 | Click-through rate                                    |
| CPC (All) (VND)     | Cost per click                                        |
| CPM (VND)           | Cost per 1,000 impressions                             |
| Cost per 1,000 people reached (VND) | Cost per 1,000 people reached                 |
| Conversions         | Number of conversions                                 |
| Conversion values   | Value of successful conversions                       |
| Cost per conversion | Cost per conversion                                   |
| Post comments       | Number of post comments                               |
| Link clicks         | Number of link clicks                                 |
| Messaging Conversations Started | Number of initiated messaging conversations |

Please note that `campaign name` follows a specific convention to facilitate easy extraction of essential information such as location and product. 

The dataset is in Vietnamese. You can download the original dataset [here](https://docs.google.com/spreadsheets/d/1ltfJFzrKwA87iO-tcMkR2FnPGTQD9Hy1hQgHvymByH8/edit?usp=sharing).

## Output

<img width="878" alt="Zoom out" src="https://github.com/thanhtruchhh/Facebook-Ads-Performance-Dashboard/assets/145547282/10b3454d-32d8-47e2-b3e3-1d99a48912f4">

<img width="898" alt="Zoom out (week, month)" src="https://github.com/thanhtruchhh/Facebook-Ads-Performance-Dashboard/assets/145547282/dd83e3d0-5f4e-4ece-8804-6884f334ff76">

<img width="890" alt="Zoom in" src="https://github.com/thanhtruchhh/Facebook-Ads-Performance-Dashboard/assets/145547282/e3884546-bb45-48f3-a4b8-2eec4307147e">
