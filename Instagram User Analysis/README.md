
# Instagram User Analytics using SQL

## Project Overview

This project analyzes Instagram user data to extract meaningful insights using SQL queries. The analysis focuses on user engagement, marketing insights, and identifying unusual user behavior such as bot accounts.

The dataset was used to create a relational database in MySQL and various SQL queries were executed to analyze the data and generate insights.

## Tech Stack

* MySQL Workbench
* SQL
* Microsoft PowerPoint

## 🗂 Database Tables

The dataset contains multiple relational tables simulating an Instagram-like platform:

* users
* photos
* comments
* likes
* follows
* tags
* photo_tags

These tables are connected using foreign key relationships.

## 📈 Business Questions & Insights

### Rewarding the Most Loyal Users

Identified the **5 oldest users** on the platform based on account creation date.

Insight:
Users with IDs **80, 67, 63, 95, and 38** were identified as the earliest users of the platform.

---

### Identify Inactive Users

Found users who **have never posted a single photo**.

Business Value:
These users can be targeted with engagement campaigns to encourage content posting.

---

### Contest Winner (Most Liked Photo)

Determined which photo received the **highest number of likes**.

Insight:
Photo ID **145** posted by **username Zack_Kemmer93** received the highest number of likes.

---

### Hashtag Research

Identified the **top 5 most frequently used hashtags**.

Top hashtags:

* smile
* beach
* party
* fun
* concert

Business Value:
These hashtags can be used to improve content visibility and marketing campaigns.

---

### Best Day for User Registration

Analyzed which day users register the most.

Insight:
The highest number of user registrations occurred on **Thursday and Sunday**.

Business Value:
Marketing campaigns can be scheduled around these days for better reach.

---

## Investor Metrics

### User Engagement

Calculated the **average number of photos uploaded per user**.

Insight:
Average photos uploaded per user = **2.57**

This metric helps evaluate user engagement on the platform.

---

### Bots & Fake Accounts Detection

Identified potential **bot accounts** by finding users who liked **every photo on the platform**, which is unusual behavior for normal users.

Insight:
Several accounts were detected that liked all photos, indicating possible automated or bot activity.

---

## Project Files

* `dataset/ig_clone_dataset.sql` → SQL script to recreate the database
* `presentation/Instagram_User_Analytics.pptx` → Contains SQL queries, output screenshots, and insights

---

##  Author

**MD. Nazish Taj**
