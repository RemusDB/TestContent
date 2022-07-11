# Part: Analyzing and visualizing data
id: anal-viz
url: anal-viz

## Description

Identify different types of data visualizations for analyzing supermarket sales data. You’ll do this by building KPI charts, bar charts and treemaps. Additionaly, you will learn which visualization to choose to deliver effective insights.

## Welcome Message

Hi and welcome to the PowerBI Fundamentals course! This course is specially designed to offer a hands-on guided-learning approach that helps you meet your goals quickly, gain confidence, and learn at your own pace. 

## Summary Message

Congrats! You have successfully completed the first part of the PowerBI Fundamentals course! In the next parts we will further deep dive into developing your data-driven decision making skills!


### Section: Types of data visualization
id: types-data
url: types-data

#### Exercise: KPIs and tables##################
id: add-title1
url: add-title1
type: video
video: https://vimeo.com/654067950

#### Exercise: Bar charts##################
id: add-title2
url: add-title2
type: video
video: https://vimeo.com/654067950

#### Exercise: Line charts##################
id: add-title3
url: add-title3
type: video
video: https://vimeo.com/654067950

#### Exercise: Scatterplots##################
id: add-title4
url: add-title4
type: video
video: https://vimeo.com/654067950

### Section: Build simple visualizations
id: custom-simple
url: custom-simple

<!--#### Exercise: Create KPIs dashboard##################
id: add-title5
url: add-title
type: video
video: https://vimeo.com/719854034/d33db34e3f-->


#### Exercise: Decisions and data visualization##################
id: decisions-data
url: decisions-data
type: video
video: https://vimeo.com/727913025/f65fbf8f39

#### Exercise: Compare with bar charts##################
id: compare-barcharts
url: compare-barcharts
type: video
video: https://vimeo.com/722307833/88e7653ce4

#### Exercise: Analyze profit data###########
id: sales-by-country
url: sales-by-country
type: powerbi
video: https://vimeo.com/722307833/88e7653ce4


##### Context

<p>Now that you are more familiar with building bar charts to visualize the FoodTiger supermarkets sales data, let's practice.</p>

##### Instructions

###### Step #1

<p>Load the 3.1_SalesComparison.twbx file</p>

####### Step Hint 

<p>To open the workbook, click on File -> Open... in the upper menu</p>

###### Step #2

<p>Now let's add some data to the visual. Go to the Data Pane on the left hand-side, select the Country column and drag it to Rows section. Similarly, drag and drop the Customer Segment column.</p>

####### Step Hint 

<p>Drag and drop the columns from the Data Pane in the left.</p>

###### Step #3

<p>Now drag the Profit column to the Columns section.</p>

####### Step Hint
 
<p>Drag and drop the column in the Fields Pane</p>

##### Task
type: multichoice
answer: 3

###### Question

<p>Which is the most profitable customer segment in Belgium?</p>

###### Option #1

<p>Discount</p>

####### Option Feedback

<p>Not quite, look cloosely at the bar chart.</p>

###### Option #2

<p>Loyal</p>

####### Option Feedback

<p>Try again! Look closely and compare the bar charts.</p>

###### Option #3

<p>New</p>

####### Option Feedback

<p>Yes, indeed! New customer are generating the highest profit!</p>

###### Hint

<p>Choose one of the provided options.</p>

#### Exercise: Drill down more###########
id: sales-by-gender
url: sales-by-gender
type: powerbi
video: https://vimeo.com/722307833/88e7653ce4


##### Context

<p>In this exercise you will explore the FoodTiger supermarkets sales data even further by adding more granularity in your barcharts.</p>

##### Instructions

###### Step #1

<p>Drag the Profit measure to Columns section.</p>

####### Step Hint 

<p>Simply drag and drop the Profit measure column to the Rows section in the upper part of the Worksheet.</p>

###### Step #2

<p>Similarly to the last step, drag the Country, Customer Segment and Product Category dimensions one by one to the Rows section.</p>

####### Step Hint 

<p>Go to NULL values, right click on NULL and then Exclude.</p>

###### Step #3

<p>Select the Gender dimenion and drag it to the Color section under Marks.</p>

####### Step Hint 

<p>The Color section is located under Marks (between the Data Pane and the Worksheet)</p>

###### Step #4

<p>Now, on the right hands side you know have 3 different values for gender: Male, Female and NULL. We want to remove the NULL values. To do this, right click on NULL and click Exclude</p>

####### Step Hint 

<p>The Gender color-scheme with Male, Female and NULL will appear on the left-hand side of the screen. Simpli right-click on NULL and select Exclude.</p>


##### Task
type: open
answer: Seafood

###### Question

<p>Which product category generates highest profit amoung Females in Germany who are Discount-seekers?</p>

###### Hint

<p>Choose one of the provided options.</p>


#### Exercise: Identify trends with line charts##################
id: identify-trends
url: identify-trends
type: video
video: https://vimeo.com/724208470/142705f2bb

#### Exercise: Anticipate profit trends ###########
id: sales-trends
url: sales-trends
type: powerbi
video: https://vimeo.com/722307833/88e7653ce4


##### Context

<p>In this exercise you will build a line chart to visualize the FoodTiger Supermakrets profit evolution and identify the trend in order to decide the sales strategy for the next period.</p>

##### Instructions

###### Step #1

<p>Drag the Order Date measure to Columns section.</p> 

<p>Do note that Tableau aggregates the date by year, and creates column headers.</p>

####### Step Hint 

<p>Simply drag and drop the Order Date measure column to the Columns section in the upper part of the Worksheet.</p>

###### Step #2

<p>Click the drop-down arrow in the Year(Order Date) field on the Columns and select More->Weekday to change the aggregation level from year to weekday.</p>

####### Step Hint 

<p>Hover the mouse over the Year(Order Date) field so that the drop-down arrow will appear. The More section is right under Day and Wekkday is the second option.</p>

###### Step #3

<p>Drag the Profit dimension to Rows section.</p>

####### Step Hint 

<p>Simply drag and drop the Profit dimension column to the Columns section in the upper part of the Worksheet.</p>

###### Step #4

<p>Switch the view from the Data Pane to the Analytics Pane.</p>

<p>To add a trendline, drag the Trend Line model to the view.</p>

####### Step Hint 

<p>Analytics Pane is situated next to the Data Pane.</p>


##### Task
type: multichoice
answer: 2

###### Question

<p>By analzying the char you build, how would you describe the weekday profit trend??</p>

###### Option #1

<p>The overall trend shows a decrease in profit, with a minimum on Tuesday.</p>

####### Option Feedback

<p>Please analyze the chart again.</p>

###### Option #2

<p>The trend line is showing an increase in profit level twords the end of the week, with a peak on Friday.</p>

####### Option Feedback

<p>That's correct!</p>

###### Option #3

<p>The overall trend is stable, without significant up or down variations.</p>

####### Option Feedback

<p>There is a trend, take a closer look at the chart.</p>

###### Hint

<p>Choose one of the provided options.</p>


#### Exercise: Choosing effective visuals for sales evolution
id: line-charts
url: line-charts
type: quiz

##### Content

<p>By now you are already faimilar with how to build different visualizations, including line charts and bar charts.<p>


<p>To deliver a strong visual data storytelling message, the question around which visualization is best to use when appears.<p>

<p>You are analyzing the FoodTiger Sales dashboard:<p>

<p align="middle"><img src="https://docs.google.com/spreadsheets/d/e/2PACX-1vStyV0dE74Z_9-X0lLky7e5MQlOfUGwwDA2RdL7iADARlWoZHuGHN4JFsxb0G6rqGF3zqofl2bQZbdR/pubchart?oid=1267966403&format=image" 
alt="recursion" align="middle" style="max-width: 100%"></p>


<p align="middle"><img src="https://docs.google.com/spreadsheets/d/e/2PACX-1vStyV0dE74Z_9-X0lLky7e5MQlOfUGwwDA2RdL7iADARlWoZHuGHN4JFsxb0G6rqGF3zqofl2bQZbdR/pubchart?oid=355589180&format=image" 
alt="recursion" align="middle" style="max-width: 100%"></p>


##### Task: Choose the most effective visual
type: multichoice
answer: 1

###### Question

<p>Which visual would you choose to focus the attention more on the trend rather than on invidiual values?</p>

###### Option #1

<p>Option A</p>

####### Option Feedback

<p>Indeed, using lines makes it easier to identify trends.</p>

###### Option #2

<p>Option B</p>

####### Option Feedback

<p>This visual is not the best option if you want to concentrate on the trend.</p>

###### Option #3

<p>Both options</p>

####### Option Feedback

<p>Not quite, one of the charts makes it easier to concentrate on the trends.</p>

###### Hint

<p>Choose one of the provided options.</p>


#### Exercise: Show composition##################
id: show-comp
url: show-comp
type: video
video: https://vimeo.com/722959322/800e2a2b45


#### Exercise: Find correlations with scatterplots##################
id: identify-correl
url: identify-correl
type: video
video: https://vimeo.com/722959322/800e2a2b45

#### Exercise: Identify correlation type
id: multichoice-correlation
url: multichoice-test-knowledge
type: quiz

##### Content

<p>You are looking at the reports from last year and the chart on sales and profit relationship gets your attention:<p>


<p align="middle"><img src="https://drive.google.com/uc?export=download&id=1LcAoo51Q1jDtKLwEXqPy4YihBMEoW0or" alt="recursion" align="middle" style="max-width: 100%"></p>


##### Task: Indentify the correlation type
type: multichoice
answer: 2

###### Question

<p>What type of correlatoin between sales and profit do you see and what does this mean?</p>

###### Option #1

<p>Negative correlation. As sales increase, the profit level will decrease</p>

####### Option Feedback

<p>Not quite, there is a different type of correlation between sales and profit.</p>

###### Option #2

<p>Positive correlation. As sales increase, the profit level will also increase.</p>

####### Option Feedback

<p>That's correct! From the chart you can see that the increase in sales generates an increase in profit also, meaning that there is a positive correlation between the variables.</p>

###### Option #3

<p>No correlation, there is no relationship between sales and profit.</p>

####### Option Feedback

<p>Not quite, if you look closer you realize that there is a relationship between sales and profit.</p>

###### Hint

<p>Choose one of the provided options.</p>


#### Exercise: Drill-down on scatterplots###########
id: drill-down
url: drill-down
type: powerbi
video: https://vimeo.com/722681929/3c493f6c4b


##### Context

<p>Scatterplots can be useful for showing relationships between two things, like profit and sales. In this exercise you will learn how to better understand the underlying relationships between sales and profit</p>

##### Instructions

###### Step #1

<p>Load the 4.2 ScatterPlot.twbx file.</p>

####### Step Hint 

<p>To open the workbook, click on File -> Open... in the upper menu.</p>

###### Step #2

<p>Drag the Profit measure to Columns. Similarly, drag the Sales measure to Rows.</p>

####### Step Hint 

<p>Drag and drop the columns from the Data Pane in the left.</p>

###### Step #3

<p>Drag the Gender dimension to Color on the Marks card.</p>

####### Step Hint
 
<p>Drag and drop the column in the Fields Pane.</p>

###### Step #4

<p>Drag the ProductCategory dimension to Detail on the Marks card.</p>

####### Step Hint
 
<p>Detail tab is right under Color.</p>


##### Task
type: open
answer: Bread

###### Question

<p>Which is the ProductCategory shoped by Male that is generating the biggest loss for FoodTiger Supermarkets?</p>

###### Hint

<p>Take a close look at the Sales & Profit scatter plot and visually identify the corresponding male circle.</p>

###### Success Feedback

<p>That’s right!</p>

###### Failure Feedback

<p>Not quite, look closely again!</p>

#### Exercise: Analyze traffic distribution ##################
id: analyze-trafic
url: analyze-trafic
type: video
video: https://vimeo.com/722959322/800e2a2b45

### Section: Customize your visualizations
id: choose-effective
url: choose-effective

#### Exercise: Filtering and sorting##################
id: filtering-sorting
url: filtering-sorting
type: video
video: https://vimeo.com/654067950

#### Exercise: Aggregations##################
id: data-aggr
url: data-aggr
type: video
video: https://vimeo.com/654067950

#### Exercise: Caclulated fields##################
id: calc-fields
url: calc-fields
type: video
video: https://vimeo.com/654067950

#### Exercise: Tips and tricks##################
id: tips-tricks
url: tips-tricks
type: video
video: https://vimeo.com/654067950

