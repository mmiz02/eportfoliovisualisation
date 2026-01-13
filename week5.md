** Week 5: Data Transformation and EDA**

In Week 5, I engaged with a practical seminar focused on data transformation and exploratory data analysis (EDA) using R, specifically through the dplyr and ggplot2 packages. The session used the nycflights13 dataset to explore realistic, high-volume data, which helped contextualise the importance of structured data manipulation prior to visualisation.

One of the key skills I developed during this week was the systematic use of core dplyr verbs such as filter(), select(), mutate(), group_by(), and summarise(). Working through these examples reinforced how data transformation directly influences the quality and clarity of visual outputs. For example, creating derived variables such as flight speed and delay recovery (gain) made it easier to explore more meaningful relationships in the data, rather than relying solely on raw variables.

The exploratory visualisations produced using ggplot2 were particularly effective in highlighting patterns, outliers, and data quality issues. Histograms revealed the heavily right-skewed nature of flight delays, while boxplots and scatterplots helped compare delays across carriers and explore relationships between distance and air time. Applying axis limits and log transformations demonstrated how visual design choices can significantly impact interpretation, reinforcing the importance of thoughtful visual encoding rather than default settings.

The integrated case study on airline punctuality was especially valuable, as it combined data cleaning, summarisation, and visualisation to support decision-making. Producing bar charts and line plots to compare carrier and monthly performance showed how visualisations can be tailored to answer specific analytical questions, aligning closely with the module’s learning outcomes.

Overall, this week strengthened my understanding of how reproducible, programming-based visualisation tools such as R and ggplot2 support rigorous analysis and transparent communication. It also helped me critically evaluate when such tools are most appropriate compared to proprietary BI software, particularly in scenarios requiring automation, reproducibility, and detailed analytical control.
still need exampleee
Examples:
Write R code to answer:
a) How many flights were cancelled (use is.na(dep_time))?
b) How many flights left more than 3 hours late but arrived on time or early?
