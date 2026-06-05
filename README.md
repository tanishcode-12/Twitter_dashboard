<div align="center">

# 🐦 Tweet Analysis Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![CSV](https://img.shields.io/badge/Data-CSV-green?style=for-the-badge&logo=databricks&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)
![Internship](https://img.shields.io/badge/Internship-2026-blue?style=for-the-badge)

<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcDd3eDlrcWd4NHFia3UwMHd2eXdtNHpxdmJ4eTNyeXQ2aGsyMGtuMyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3oKIPEqDGUULpEU0aQ/giphy.gif" width="400"/>

### 📊 A Power BI internship project analyzing Twitter engagement data across 6 tasks
### Built using two dataset versions covering tweet interactions, media performance, and engagement trends for 2020 🗓️

</div>

---

## 📁 Repository Structure

```
📦 tweet-analysis-dashboard/
 ┣ 📄 README.md
 ┣ 📂 data/
 ┃ ┣ 📊 SocialMedia.csv                  ← Original dataset (twitter.pbix)
 ┃ ┗ 📊 SocialMedia_updated (4).csv      ← Enriched dataset (twitter2.pbix)
 ┣ 📂 reports/
 ┃ ┣ 📈 twitter.pbix                     ← Dashboard v1 — original data
 ┃ ┗ 📈 twitter2.pbix                    ← Dashboard v2 — updated data ✅
 ┗ 📂 docs/
   ┗ 📄 Dashboard_Limitations.pdf        ← Limitations report (twitter.pbix only)
```

---

## 🌟 Project Overview

<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExanIwYjR1NWZxbjgwNmV3NXY5NHpqNW9lOGM3NHFtNGZ2dGJ3bHFkbCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/l0HlNQ03J5JxX6lva/giphy.gif" width="320" align="right"/>

This project builds an **interactive Power BI dashboard** to analyze tweet performance across six tasks. Two report versions exist:

- 🐣 `twitter.pbix` — built on the original dataset
- 🚀 `twitter2.pbix` — built on an enriched dataset where **all tasks are fully and correctly implemented**

| | 🐣 twitter.pbix | 🚀 twitter2.pbix |
|---|---|---|
| 📂 Data source | `SocialMedia.csv` | `SocialMedia_updated (4).csv` |
| 🔢 Rows | 1,181 | 1,181 |
| 📋 Columns | 21 | 47 |
| 📅 Date coverage | Jun–Oct 2020 | Jan–Dec 2020 ✅ |
| ❗ Missing values | Yes | None ✅ |
| ✅ All tasks fully implemented | No | **Yes** ✅ |

---

## 📺 Dashboard Pages

<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExeTZ3NHZ2NmNwcGpzanQxMGRzdGozemR2Z3hwYXlhNG82dGZzNHlmYyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/26tn33aiTi1jkl6H6/giphy.gif" width="300"/>

All three pages exist in both report versions:

| 📄 Page | 📊 Contents |
|---|---|
| 💬 **Interaction & Engagement** | URL clicks, profile clicks, and hashtag clicks by tweet category |
| 🎬 **Media & Trends** | Media views and engagements by day of week; monthly engagement rate trend |
| 🏆 **Performance** | Top tweets by engagement; replies, retweets, and likes comparison |

---

## ✅ Tasks

<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNWQ3eTR6NWozemd3dTQ4NHNlcm16NW16Mmd3MHpsMzlpbjBhazlpaCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/du3J3cXyzhj75IOgvA/giphy.gif" width="280" align="right"/>

### 🔵 Task 1 — Tweet Interaction Breakdown by Category
Clustered bar chart showing **sum of URL clicks, user profile clicks, and hashtag clicks** grouped by tweet category (media, links, hashtags).

- 📅 Filtered to even tweet dates
- 🔢 Word count > 40
- 🕒 Visible only between **3 PM–5 PM IST**

---

### 🟣 Task 2 — Engagement Rate: App Opens vs No App Opens
Compares **average engagement rate** for tweets with and without app opens.

- 📅 Weekday tweets only
- 🕘 Posted between **9 AM–5 PM IST**
- 🔢 Even impressions, odd dates, char count > 30
- 🚫 Excludes tweets containing the letter **'D'**
- 🕛 Active between **12 PM–6 PM IST** and **7 AM–11 AM IST**

---

### 🟠 Task 3 — Media Interaction by Day of Week
Dual-axis chart showing **media views and media engagements** by day of week.

- 📅 Even impressions, odd dates, char count > 30
- 🚫 Excludes tweets containing the letter **'H'**
- 🕒 Visible between **3 PM–5 PM IST** and **7 AM–11 AM IST**
- ✅ Day of Week correctly used on X-axis with `DayOfWeekNum` sort column

---

### 🟡 Task 4 — Replies, Retweets, and Likes Comparison
Simple bar chart comparing **SUM of replies, retweets, and likes** for June–August 2020.

| 💬 Replies | 🔁 Retweets | ❤️ Likes |
|---|---|---|
| 3,712 | 11,710 | 26,093 |

---

### 🟢 Task 5 — Monthly Engagement Rate Trend
Line chart showing **average engagement rate per month** across all 12 months of 2020.

- 📈 Two lines: tweets **with media** vs **without media**
- 🗓️ Full January–December 2020 coverage

---

### 🔴 Task 6 — Top 10 Tweets by Engagement
Bar chart identifying the **top 10 tweets** by sum of retweets + likes.

- 📅 Weekday only, odd dates, even impressions
- 🔢 Word count < 30
- 👤 Username displayed per tweet
- 🕒 Visible between **3 PM–5 PM IST**

---

## 🗃️ Data Notes

<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExMnltbjQxaHhnaHk3cGd4NHlrNGJ3aGt6eTlwbGczY2trZzI3cXZkbSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3oKIPnAiaMCws8nOsE/giphy.gif" width="300"/>

### 🐣 SocialMedia.csv — twitter.pbix
- 📋 1,181 rows, 21 columns
- ⚠️ Small number of missing values in `impressions`, `media views`, `media engagements`
- 📅 Covers June–October 2020 only
- 📄 See `docs/Dashboard_Limitations.pdf` for documented adjustments

### 🚀 SocialMedia_updated (4).csv — twitter2.pbix
- 📋 1,181 rows, 47 columns — **zero missing values** ✅
- 🧮 26 additional computed columns: `Tweet Category`, `Has Media`, `Has App Opens`, `Engagement Category`, `Day of Week`, `Month`, `Word Count`, `Char Count`, `Username` and more
- 📅 Full year coverage: **January–December 2020** ✅
- 🔥 Most active months: August (313 tweets), July (306), June (286)

---

## 🚀 How to Open

<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcjgxNGQ3d2lrdzc2dXBna3ZzcnF4dWFxZDVsanl0dGlxZjZzbjYwdyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/Ln2dAW9oycjgmTpjX9/giphy.gif" width="280" align="right"/>

1. 📥 Download the `.pbix` file from the `reports/` folder
2. 💻 Open with [Power BI Desktop](https://powerbi.microsoft.com/desktop/) *(free)*
3. 🔗 If prompted about the data source, point it to the corresponding CSV in `data/`
4. 🎉 Explore the dashboard!

---

## 🛠️ Requirements

| Tool | Details |
|---|---|
| 💛 Power BI Desktop | Any recent version (built on v2.154.778.0) |
| 📊 Data files | Included in `data/` folder |
| 🔌 External connectors | None required |
| 💰 Premium features | None required |

---

## 📝 Notes on twitter.pbix

The original dashboard (`twitter.pbix`) was built on a dataset with certain constraints. All documented adjustments and known limitations for that version are covered in [`docs/Dashboard_Limitations.pdf`](docs/Dashboard_Limitations.pdf). 

The updated dashboard (**`twitter2.pbix`**) addresses all of these and implements **every task requirement fully** as specified. 🎯

---

<div align="center">

<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExdWk3eXo5NHZ6NTBwdWF6NXV4dXp2NHprcm56MGw3NmZhcTEzdWFrayZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3ohzdIuqJoo8QdKlnW/giphy.gif" width="200"/>

### ⭐ If you found this useful, give it a star! ⭐

*🎓 Internship project — Power BI implementation, 2026 🎓*

</div>
