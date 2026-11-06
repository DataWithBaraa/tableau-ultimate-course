# Tableau Ultimate Course

[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@datawithbaraa) [![Udemy](https://img.shields.io/badge/Udemy-A435F0?style=for-the-badge&logo=udemy&logoColor=white)](https://www.udemy.com/course/the-tableau-ultimate-course-from-zero-to-hero/?referralCode=6544726FDC491A6B25EC) [![Website](https://img.shields.io/badge/datawithbaraa.com-111111?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.datawithbaraa.com) [![License](https://img.shields.io/github/license/DataWithBaraa/tableau-ultimate-course?style=for-the-badge&color=2EA043)](LICENSE) [![Stars](https://img.shields.io/github/stars/DataWithBaraa/tableau-ultimate-course?style=for-the-badge&color=F5B301)](https://github.com/DataWithBaraa/tableau-ultimate-course)

The materials of the Tableau course: the datasets, the slides, the finished workbook of every section, and the two dashboard projects.

⭐ If this course helps you, star the repository so other learners can find it too.

**New here? Open the setup guide in the `00_setup` folder.** It walks you through installing Tableau Public on Windows and Mac and picking the right dataset, with the fixes for the common errors.

```
tableau-ultimate-course/
├── 00_setup/                     the setup guide
├── 01_datasets/                  the course data, in two versions
│   ├── eu/                       decimal numbers with a comma: 12,5
│   │   ├── small-dataset/        a few rows, to follow every step of a calculation
│   │   └── big-dataset/          5 years of orders, for aggregations and LOD
│   └── non-eu/                   the same files with a dot: 12.5
├── 02_docs/                      the slides and the cheat sheets, as PDF
├── 03_workbooks/                 the finished workbook of every section (.twbx)
└── 04_projects/                  the two end-to-end projects, each with its requirements
    ├── sales-dashboard-project/  the sales and customer dashboards
    └── hr-dashboard-project/     the HR dashboard
```

**EU or non-EU?** Take `eu` if you are in Europe, `non-eu` everywhere else. To be sure, connect `Orders.csv` in Tableau: Sales, Profit and Discount must show the green number icon (#). If they show Abc, take the other folder.

<details>
<summary><b>The 68 chapters</b>: the minute in the video, and the slides and workbook of each section</summary>

| # | Chapter | Video | Slides | Workbook |
|--:|:--|:--|:--|:--|
| 1 | Intro | [0:00:00](https://youtu.be/K3pXnbniUcM?t=0) |  |  |
| 2 | Tableau Course Structure | [0:03:20](https://youtu.be/K3pXnbniUcM?t=200) |  |  |
| 3 | Big Data Terms | [0:08:37](https://youtu.be/K3pXnbniUcM?t=517) | [Section01 Tableau-Basics](02_docs/Section01_Tableau-Basics.pdf) |  |
| 4 | What is Business Intelligence (BI) | [0:16:54](https://youtu.be/K3pXnbniUcM?t=1014) |  |  |
| 5 | What is Data Visualization | [0:19:34](https://youtu.be/K3pXnbniUcM?t=1174) |  |  |
| 6 | Excel vs BI-Tools | [0:22:50](https://youtu.be/K3pXnbniUcM?t=1370) |  |  |
| 7 | Top 3 BI-Tools | [0:31:28](https://youtu.be/K3pXnbniUcM?t=1888) |  |  |
| 8 | What is Tableau | [0:32:22](https://youtu.be/K3pXnbniUcM?t=1942) |  |  |
| 9 | Why Tableau | [0:34:50](https://youtu.be/K3pXnbniUcM?t=2090) |  |  |
| 10 | Tableau Development Products | [0:39:54](https://youtu.be/K3pXnbniUcM?t=2394) | [Section02 Tableau-Products](02_docs/Section02_Tableau-Products.pdf) |  |
| 11 | Tableau Sharing Process | [0:43:36](https://youtu.be/K3pXnbniUcM?t=2616) |  |  |
| 12 | Tableau Hosting (OnPrem, IaaS, SaaS) | [0:54:26](https://youtu.be/K3pXnbniUcM?t=3266) |  |  |
| 13 | Tableau Sharing Products | [1:00:24](https://youtu.be/K3pXnbniUcM?t=3624) |  |  |
| 14 | #3 Section: Tableau Architecture | [1:12:03](https://youtu.be/K3pXnbniUcM?t=4323) | [Section03 Tableau-Architectures](02_docs/Section03_Tableau-Architectures.pdf) |  |
| 15 | Live vs Extract | [1:12:46](https://youtu.be/K3pXnbniUcM?t=4366) |  |  |
| 16 | Tableau File Types | [1:14:48](https://youtu.be/K3pXnbniUcM?t=4488) |  |  |
| 17 | Tableau Desktop Architecture | [1:19:16](https://youtu.be/K3pXnbniUcM?t=4756) |  |  |
| 18 | Tableau Server Architecture | [1:26:39](https://youtu.be/K3pXnbniUcM?t=5199) |  |  |
| 19 | Download & Install Tableau Public | [1:48:44](https://youtu.be/K3pXnbniUcM?t=6524) | [the setup guide](00_setup) |  |
| 20 | Create Tableau Public Account | [1:50:06](https://youtu.be/K3pXnbniUcM?t=6606) |  |  |
| 21 | Get Training Datasets | [1:51:26](https://youtu.be/K3pXnbniUcM?t=6686) |  |  |
| 22 | Publish First Viz | [1:57:18](https://youtu.be/K3pXnbniUcM?t=7038) |  |  |
| 23 | Tour into the Tableau Interface | [1:59:33](https://youtu.be/K3pXnbniUcM?t=7173) |  |  |
| 24 | #5 Section: Combining Data | [2:13:01](https://youtu.be/K3pXnbniUcM?t=7981) | [Section05 Data-Modeling](02_docs/Section05_Data-Modeling.pdf) | [Section 05 - Data Sources](03_workbooks/Section%2005%20-%20Data%20Sources.twbx) |
| 25 | Basics Data Modeling | [2:13:51](https://youtu.be/K3pXnbniUcM?t=8031) |  |  |
| 26 | Logical & Physical Layers | [2:19:57](https://youtu.be/K3pXnbniUcM?t=8397) |  |  |
| 27 | Joins | [2:25:07](https://youtu.be/K3pXnbniUcM?t=8707) |  |  |
| 28 | Union | [2:33:59](https://youtu.be/K3pXnbniUcM?t=9239) |  |  |
| 29 | Relationships | [2:40:54](https://youtu.be/K3pXnbniUcM?t=9654) |  |  |
| 30 | Data Blending | [2:57:28](https://youtu.be/K3pXnbniUcM?t=10648) |  |  |
| 31 | Summary: Combining Methods | [3:15:57](https://youtu.be/K3pXnbniUcM?t=11757) |  |  |
| 32 | #6 Section: Tableau Metadata | [3:28:46](https://youtu.be/K3pXnbniUcM?t=12526) | [Section06 Tableau-Metadata](02_docs/Section06_Tableau-Metadata.pdf) | [Section 06 - Metadata](03_workbooks/Section%2006%20-%20Metadata.twbx) |
| 33 | Data Types | [3:29:42](https://youtu.be/K3pXnbniUcM?t=12582) |  |  |
| 34 | Geographic & Image Roles | [3:48:35](https://youtu.be/K3pXnbniUcM?t=13715) |  |  |
| 35 | Dimensions & Measures | [3:53:18](https://youtu.be/K3pXnbniUcM?t=13998) |  |  |
| 36 | Discrete vs Continuous | [4:10:57](https://youtu.be/K3pXnbniUcM?t=15057) |  |  |
| 37 | Summary: Tableau Metadata | [4:25:34](https://youtu.be/K3pXnbniUcM?t=15934) |  |  |
| 38 | #7 Section: Renaming & Aliases | [4:27:16](https://youtu.be/K3pXnbniUcM?t=16036) | [Section07 Renaming-Aliases](02_docs/Section07_Renaming-Aliases.pdf) | [Section 07 - Renaming](03_workbooks/Section%2007%20-%20Renaming.twbx) |
| 39 | Naming Conventions | [4:27:50](https://youtu.be/K3pXnbniUcM?t=16070) |  |  |
| 40 | Renaming | [4:38:28](https://youtu.be/K3pXnbniUcM?t=16708) |  |  |
| 41 | Aliases | [4:48:46](https://youtu.be/K3pXnbniUcM?t=17326) |  |  |
| 42 | #8 Section: Organizing Data | [4:57:26](https://youtu.be/K3pXnbniUcM?t=17846) | [Section08 Organizing-Data](02_docs/Section08_Organizing-Data.pdf) | [Section 08 - Organizing Data](03_workbooks/Section%2008%20-%20Organizing%20Data.twbx) |
| 43 | Hierarchy | [4:58:13](https://youtu.be/K3pXnbniUcM?t=17893) |  |  |
| 44 | Groups | [5:16:03](https://youtu.be/K3pXnbniUcM?t=18963) |  |  |
| 45 | Cluster Group | [5:28:57](https://youtu.be/K3pXnbniUcM?t=19737) |  |  |
| 46 | Sets | [5:38:37](https://youtu.be/K3pXnbniUcM?t=20317) |  |  |
| 47 | Bins & Histograms | [6:02:25](https://youtu.be/K3pXnbniUcM?t=21745) |  |  |
| 48 | #9 Section: Filtering & Sorting Data | [6:12:55](https://youtu.be/K3pXnbniUcM?t=22375) | [Section09 Tableau-Filters](02_docs/Section09_Tableau-Filters.pdf) | [Section 09 - Filtering Data](03_workbooks/Section%2009%20-%20Filtering%20Data.twbx) |
| 49 | Understand Tableau Filters | [6:13:40](https://youtu.be/K3pXnbniUcM?t=22420) |  |  |
| 50 | How to Create Filters | [6:25:11](https://youtu.be/K3pXnbniUcM?t=23111) |  |  |
| 51 | Customizing Filters | [6:48:05](https://youtu.be/K3pXnbniUcM?t=24485) |  |  |
| 52 | #10 Section: Tableau Parameters | [8:03:50](https://youtu.be/K3pXnbniUcM?t=29030) |  | [Section 10 - Parameters](03_workbooks/Section%2010%20-%20Parameters.twbx) |
| 53 | #11 Section: Tableau Actions | [8:32:09](https://youtu.be/K3pXnbniUcM?t=30729) | [Section11 Tableau-Actions](02_docs/Section11_Tableau-Actions.pdf) | [Section 11 - Actions](03_workbooks/Section%2011%20-%20Actions.twbx) |
| 54 | #12 Section: Tableau Calculations | [9:05:56](https://youtu.be/K3pXnbniUcM?t=32756) |  | [Section 12 - Aggregate Calculations](03_workbooks/Section%2012%20-%20Aggregate%20Calculations.twbx) · [Section 12 - LOD Expressions](03_workbooks/Section%2012%20-%20LOD%20Expressions.twbx) · [Section 12 - Row Level Calculations (Functions)](03_workbooks/Section%2012%20-%20Row%20Level%20Calculations%20%28Functions%29.twbx) · [Section 12 - Table Calculations](03_workbooks/Section%2012%20-%20Table%20Calculations.twbx) |
| 55 | Types of Tableau Calculations | [9:31:33](https://youtu.be/K3pXnbniUcM?t=34293) |  |  |
| 56 | Number Functions | [9:53:53](https://youtu.be/K3pXnbniUcM?t=35633) |  |  |
| 57 | String Functions | [10:04:12](https://youtu.be/K3pXnbniUcM?t=36252) |  |  |
| 58 | Date Functions | [11:27:55](https://youtu.be/K3pXnbniUcM?t=41275) |  |  |
| 59 | Null Functions | [12:17:31](https://youtu.be/K3pXnbniUcM?t=44251) |  |  |
| 60 | Logical Functions | [12:30:33](https://youtu.be/K3pXnbniUcM?t=45033) |  |  |
| 61 | Aggregate Functions | [13:16:13](https://youtu.be/K3pXnbniUcM?t=47773) |  |  |
| 62 | Attribute Function ATTR() | [13:35:24](https://youtu.be/K3pXnbniUcM?t=48924) |  |  |
| 63 | Fixed | [13:59:29](https://youtu.be/K3pXnbniUcM?t=50369) |  |  |
| 64 | Exclude | [14:08:55](https://youtu.be/K3pXnbniUcM?t=50935) |  |  |
| 65 | Include | [14:14:26](https://youtu.be/K3pXnbniUcM?t=51266) |  |  |
| 66 | #13 Section: Tableau Charts | [15:02:51](https://youtu.be/K3pXnbniUcM?t=54171) |  | [Section 13 - Multi-Measures](03_workbooks/Section%2013%20-%20Multi-Measures.twbx) · [Section 13 - Tableau 63 Charts](03_workbooks/Section%2013%20-%20Tableau%2063%20Charts.twbx) |
| 67 | #14 Section: Tableau Dashboards | [17:55:35](https://youtu.be/K3pXnbniUcM?t=64535) | [Section14 Tableau-Dashboards](02_docs/Section14_Tableau-Dashboards.pdf) | [Section 14 - Tableau Dashboard](03_workbooks/Section%2014%20-%20Tableau%20Dashboard.twbx) |
| 68 | #15 Section: Tableau Project | [18:22:08](https://youtu.be/K3pXnbniUcM?t=66128) | [Section15 Tableau-Project](02_docs/Section15_Tableau-Project.pdf) | [Section 15 - Tableau Sales & Customer Dashboards](03_workbooks/Section%2015%20-%20Tableau%20Sales%20%26%20Customer%20Dashboards.twbx) |

The cheat sheets: [Cheat sheet Tableau-Concepts](02_docs/Cheat-Sheet._Tableau-Concepts.pdf) · [Cheat sheet Tableau Charts](02_docs/Cheat-Sheet_Tableau%20Charts.pdf) · [Cheat sheet Tableau-Functions](02_docs/Cheat-Sheet_Tableau-Functions.pdf) · [Cheat sheet Tableau-Slides](02_docs/Cheat-Sheet_Tableau-Slides.pdf).

</details>

---

## 🎓 Learn with me

Watch on YouTube, or take the guided version with a certificate on my Academy or Udemy.

| Course | YouTube | My Academy | Udemy |
|:--|:--|:--|:--|
| **SQL** | [Full course](https://youtu.be/SSKVgrwhzus) · [Playlist](https://www.youtube.com/playlist?list=PLNcg_FV9n7qZY_2eAtUzEUulNjTJREhQe) | [Full Package](https://www.datawithbaraa.com/course/sql-full-course-for-beginners) · [Handbook](https://academy.datawithbaraa.com/l/digital_download/1087406/the-sql-handbook) | [SQL Bootcamp](https://www.udemy.com/course/the-complete-sql-bootcamp-30-hours-go-from-zero-to-hero/?referralCode=D20781228C2EB8B98339) · [SQL for Analytics](https://www.udemy.com/course/sql-mastery-for-data-analytics-and-business-intelligence/) |
| **Python** | [Full course](https://youtu.be/Rq5gJVxz55Q) · [Playlist](https://www.youtube.com/playlist?list=PLNcg_FV9n7qZGfFl2ANI_zISzNp257Lwn) | [Full Package](https://www.datawithbaraa.com/course/the-ultimate-python-mastery) · [Handbook](https://academy.datawithbaraa.com/l/digital_download/998313/the-python-handbook) | [Python Bootcamp](https://www.udemy.com/course/the-complete-python-bootcamp-13hours-go-from-zero-to-hero/?referralCode=776491A4119FF8AF41CA) |
| **Tableau** | [Full course](https://youtu.be/K3pXnbniUcM) · [Playlist](https://www.youtube.com/playlist?list=PLNcg_FV9n7qZJqrKcUUCWCWPYCrlcVm9v) | [Full Package](https://www.datawithbaraa.com/course/tableau-ultimate-full-course-for-beginners) | [Tableau Course](https://www.udemy.com/course/the-tableau-ultimate-course-from-zero-to-hero/?referralCode=6544726FDC491A6B25EC) · [Chart Masterclass](https://www.udemy.com/course/the-tableau-ultimate-chart-masterclass-63-tableau-charts/) |
| **Power BI** | [Full course](https://www.youtube.com/playlist?list=PLNcg_FV9n7qZge4KDGqGtqgiuVuhVZWzu) | | |
| **Databricks** | [Full course](https://www.youtube.com/playlist?list=PLNcg_FV9n7qZWchr-GE5iPPBmOjiffK6O) | | |

Materials on my website: [SQL](https://www.datawithbaraa.com/wiki/sql) · [Python](https://www.datawithbaraa.com/wiki/python) · [Tableau](https://www.datawithbaraa.com/wiki/tableau) · [Power BI](https://www.datawithbaraa.com/wiki/power-bi)

### The Tableau projects

| Project | YouTube | Requirements | Materials | Tableau Public |
|:--|:--|:--|:--|:--|
| **Sales Dashboard** | [Watch](https://youtu.be/dahrmqT5GD4) | [PDF](04_projects/sales-dashboard-project/Project_Requirements.pdf) | [sales-dashboard-project](04_projects/sales-dashboard-project) | [My vizzes](https://public.tableau.com/app/profile/baraa.salkini/vizzes) |
| **HR Dashboard** | [Watch](https://youtu.be/UcGF09Awm4Y) | [PDF](04_projects/hr-dashboard-project/Project_Requirements.pdf) | [hr-dashboard-project](04_projects/hr-dashboard-project) | same profile |

More on YouTube: [Data projects](https://www.youtube.com/playlist?list=PLNcg_FV9n7qZ4Ym8ZriYT6WF8TaC2e_R7) · [Data careers](https://www.youtube.com/playlist?list=PLNcg_FV9n7qah95jp-aPtysu7kFCbg7hd)

## 🤝 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge)](https://www.linkedin.com/in/baraa-khatib-salkini/) [![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/gsVJbMxKcA) [![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/datawithbaraa/) [![TikTok](https://img.shields.io/badge/TikTok-000000?style=for-the-badge&logo=tiktok&logoColor=white)](https://www.tiktok.com/@datawithbaraa) [![Newsletter](https://img.shields.io/badge/Newsletter-FF6719?style=for-the-badge&logo=substack&logoColor=white)](https://www.blog.datawithbaraa.com) [![Notion Roadmaps](https://img.shields.io/badge/Notion_Roadmaps-000000?style=for-the-badge&logo=notion&logoColor=white)](https://www.notion.com/@datawithbaraa)

## 🛡️ License

[MIT](LICENSE). Use it, change it, share it, with attribution.

## 🌟 About me

Hi, I'm **Baraa Khatib Salkini**. I spent years in enterprise data engineering and built one of the largest lakehouses at Mercedes-Benz. Today I teach data full-time at **Data With Baraa**: visually, step by step, from zero to hero.
