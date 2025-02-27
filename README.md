# Visualizing Labor Migration Using Quantitative Data
## Workshop Syllabus

### Instructors:
* Adam Slez, Associate Professor of Sociology
* Jon Kropko, Associate Professor of Data Science

### Course times and location:
* Monday, July 17 - Friday, July 28, 9am - 12pm
* Dell 1 Conference room (directions to Dell 1: https://goo.gl/maps/Cm2ZkUHvyZQnmqfLA)
* Hybrid format: Zoom link under "Online Meetings" on course Canvas page

### UVA Canvas
Accessible via https://canvas.its.virginia.edu

### GitHub
https://github.com/visualizinglabormigration/workshop

### Microsoft Teams
"Visualizing Labor Migration Using Quantitative Data" team (you should have an invitation to this team in your email)

### Description
Scholars, policy makers, union leaders, and development professionals have all shown an increasing interest in understanding how labor migration shapes the contours of the global political economy today. Toward this end, the goal of this two-week workshop is for students and instructors to work together to build new public-facing tools for visualizing the flow and distribution of labor migrants throughout North America. Along the way, students will be introduced to key concepts in reproducible research, data visualization, exploratory data analysis, network analysis, and spatial statistics, while gaining hands-on experience working in R—a free and powerful programming language used by social scientists, statisticians, and data scientists alike. We will focus in particular on developing skills using popular packages such as tidyverse, plotly, tidygraph, sf, spdep, and shiny. Experience using R is preferred, but not required. Participants are eligible for a $500 stipend upon completion of the workshop.

### Schedule
* Day 1: Monday, July 17 – Introduction to R, R Studio, and R Markdown
* Day 2: Tuesday, July 18 – Using tidyverse to load, manipulate, and clean data
* Day 3: Wednesday, July 19 – Visualizing and exploring data
* Day 4: Thursday, July 20 – Using tidycensus, merging data, and creating maps
* Day 5: Friday, July 21 – Linear and logistic regression models
* Day 6: Monday, July 24 – Networks 
* Day 7: Tuesday, July 25 – Exploratory spatial data analysis
* Day 8: Wednesday, July 26 – Network and spatial regression models
* Day 9: Thursday, July 27 – Dashboards and interactivity apps using Shiny, work to prepare final presentations
* Day 10: Friday, July 28 – Final presentations plus group collaboration

### Class datasets
* American Community Survey from the U.S. Census, available via the [tidycensus](https://cran.r-project.org/web/packages/tidycensus/index.html) package for R
* Historical case disclosure data for H2-A visas: https://www.dol.gov/agencies/eta/foreign-labor/performance
* ZIP codes with latitude/longitude coordinates: http://download.geonames.org/export/zip/US.zip

### Instructions for accessing R Studio via Rivanna, UVA's cloud computing environment
1. Go to https://rivanna-portal.hpc.virginia.edu/
2. Sign in with your UVA ID and password, and DUO if necessary
3. Click "My Interactive Sessions"
4. Click "R Studio Server"
5. Change "Number of Hours" to 3
6. Under "Allocation" type: SDS_Kropkoclass
7. The R Studio Server box is blue while the system loads, wait for it to turn green
8. Click "Connect to R Studio Server"
9. (Just the first time you connect) Click on "terminal" (next to "console")
10. (Just the first time you connect) Type: cd /scratch/ID where ID is your UVA compute ID (for example /scratch/jk8sd)
11. (Just the first time you connect) Type: git clone https://github.com/visualizinglabormigration/workshop/
