# world countries compared
## Data visualisation website project, comparing country statistics to each other on an interactive bar chart

Interactive Frontend development Milestone Project

This is a client-side JavaScript project.

The website allows the  user to select 8 countries from a list of over 200 countries. The countries can be compared from different statistical aspects. For example, by population or by area per square mile or by GDP per capita, etc. It is a data visualization website, showing the comparisons represented in a coloured bar chart.

On the top row of the web page there are 8 drop-down list-boxes beside each other. Each list-box contains a list of over 200 countries. The user can select one country from each of the 8 drop-down list-boxes. Each list-box has a different colour. The colour scheme corresponds to the colour scheme of the bars on the bar chart.

On the line below the list boxes there are 6 radio buttons with descriptive names for each button. Only one of the 6 radio buttons can be selected at a time. The radio button selected determines the type of statistic you want to compare. For example, if you select GDP radio button then you want to see 8 countries compared to each other by GDP per capita. The title of the bar chart changes depending on the radio button selected; this helps the user to understand the meaning of the bar chart.

There is also a sort button. When you click it then the 8 bars on the bar chart are sorted in descending order along the y-axis. In other words, the countries are rearranged in decreasing order based on the statistical value of each country.

The data for the bar chart comes from the countries.csv file inside the data folder.   
The data may be over 15 years old. This is 2019. The data originally came from the website gsociology.icaap.org/data/PD_useful.xls.
The bar chart is interactive in the sense that if you select a different country or a different radio button you see the bar chart change immediately. Some JavaScript is used to achieve this interactivity.

I got some help from the internet. In particular I copied and modified some JavaScript code written by Curran Kelleher from the website at https://bl.ocks.org/curran/fea34ca9b3b8886e3ab8 in order to render the 8 coloured bars and have the titles at the bottom of chart at a slanted angle near each bar.

Michael Finnegan, Saturday 6th July 2019
Developed at Kerry ETB, Tralee. Ireland.



