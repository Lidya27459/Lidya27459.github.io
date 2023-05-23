---
title: "Final Project<img src='/images/Maps for final project.png'><img src='/images/Maps for final project_2.png'>"
excerpt: 
collection: portfolio
---

Introduction 
---

According to a new voting and registration table released by the U.S. Census Bureau, voter turnout increased as age, educational attainment, and income increased. Knowing this fact, I want to analyze how voter turnout increased as education attainment increased.[Voting and Registration](https://www.census.gov/newsroom/press-releases/2021/2020-presidential-election-voting-and-registration-tables-now-available.html). So to do this analysis, I picked Maryland and examined for each of the counties how education background is directly proportional to voter turnout. The data is downloaded from this website [Citizen, Voting-Age Population By Educational Attainment](https://www.socialexplorer.com/data/ACS2021_5yr/metadata/?ds=ACS21_5yr&table=B29002) for the five-year 2017–2021 citizen voter population by education attainment. 

---
Once the file and data were uploaded and converted to a usable format for R Studio, I manipulated the data using applicable functions such as ggplot , geom_sf, and scale_fill_viridis_c in R Studio to filter out and plot maps that illustrate the analysis of education background and voting turnout. I also used QGIS to present polished maps that include layout.

Results 
-----
My analysis is about Maryland counties voting turnouts based on education level and observing if their educational backgrounds increase or decrease the contribution of voters in an election. The result emphasizes that the participation rate in elections is influenced by the voters’ educational background. The numerical results confirm that the number of voters’ turnout is directly proportional to their educational status. To do the analysis, I examined the voter participation rate with a high school degree, without a high school degree, associate, bachelor, and graduate degrees, and it explains that the higher the education level, the higher the voter participation. The maps above show that, as well as which counties have a higher educated population and voting turnout, such as Baltimore City, Baltimore, and Montgomery County.

