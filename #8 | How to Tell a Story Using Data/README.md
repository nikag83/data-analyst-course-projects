NOTE: If you can't visualize all of the graphs in the JupyterNotebook file in this repository, please access it from here >>
https://nbviewer.org/github/nikag83/data-analyst-course-projects/blob/main/%238%20%7C%20How%20to%20Tell%20a%20Story%20Using%20Data/%238%20-%20Data%20Storytelling%20-%20restaurant%20analysis.ipynb

## Project description
You’ve decided to open a small robot-run cafe in Los Angeles. The project is promising but expensive, so you and your partners decide to try to attract investors. They’re interested in the current market conditions—will you be able to maintain your success when the novelty of robot waiters wears off?
You’re an analytics guru, so your partners have asked you to prepare some market research. You have open-source data on restaurants in LA.

## Instructions for completing the project

### Step 1. Download the data and prepare it for analysis
Download the data on restaurants in LA. Make sure that the data type for each column is correct and that there are no missing values or duplicates. Process them if necessary. File path: /datasets/rest_data_us.csv.

### Step 2. Data analysis
- Investigate the proportions of the various types of establishments. Plot a graph.
- Investigate the proportions of chain and nonchain establishments. Plot a graph.
- Which type of establishment is typically a chain?
- What characterizes chains: many establishments with a small number of seats or a few establishments with a lot of seats?
- Determine the average number of seats for each type of restaurant. On average, which type of restaurant has the greatest number of seats? Plot graphs.
- Put the data on street names from the address column in a separate column.
- Plot a graph of the top ten streets by number of restaurants.
- Find the number of streets that only have one restaurant.
- For streets with a lot of restaurants, look at the distribution of the number of seats. What trends can you see?
- Draw an overall conclusion and provide recommendations on restaurant type and number of seats. Comment on the possibility of developing a chain. 

### Step 3. Preparing a presentation
Make a presentation of your research to share with investors. 

**Data description**

- rest_data table:
  - object_name — establishment name
  - chain — chain establishment (TRUE/FALSE)
  - object_type — establishment type
  - address — address
  - number — number of seats
