## Tableau Dashboard & Presentation
**Tableau**
https://public.tableau.com/views/TableaudashboardbyNikaGelfand-Sprint11/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

**Presentation**
https://github.com/nikag83/data-analyst-course-projects/blob/main/%2310%20%7C%20Automation%20(Tableau)/Automation%20and%20Tableau%20dashboard%20-%20by%20Nika%20Gelfand.pdf

## Project description
You work as a video ad analyst at the Sterling & Draper advertising agency. You devote a lot of time to analyzing trending videos on YouTube to determine what content deserves marketing attention. Each video has a specific category (Entertainment, Music, News & Politics, etc.), region, and trending date. A video can be in the trending section for several days in a row.

## Dashboard Requirements

After talking to the managers and database administrators, you've drawn up brief technical requirements:

**Business goal:** analyze trending-video history on YouTube

**How often the dashboard will be used:** at least once a day

**Target dashboard user:** video ads planning managers

**Dashboard data content:**

1. Trending videos from the past, broken down by day and category
Trending videos, broken down by countries
2. A table of correspondence between categories and countries
   Parameters according to which the data is to be grouped:
- Trending date and time
- Video category
- Country
  
3. The data:
- Trending history — absolute values with a breakdown by day (two graphs: absolute numbers and percentage ratio)
- Events, broken down by countries — relative values (% of events)
- The correspondence between the categories and countries — absolute values (a table)

**Importance:** all graphs are equally important

**Data sources for the dashboard:** the data engineers promised to create an aggregate table called trending_by_time. 
Here's its structure:
- record_id — primary key
- region — country/geographical region
- trending_date — date and time
- category_title — the video category
- videos_count — the number of videos in the trending section

The table is stored in the data-analyst-youtube-data. database, which was created especially for your needs
Data update interval: once every 24 hours, at midnight UTC

