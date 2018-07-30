# 360 Giving  Data Visualization Challenge
Submission for [360 Giving  Data Visualization Challenge](https://challenge.threesixtygiving.org/)

### Question - 
Who has funded what themes throughout the years?

### Solution : 
Identifying Trends by using Keywords(Themes) based filtering methodology.

### Scope of Data Analysed and Visualized. 
The [entire dataset](http://grantnav.threesixtygiving.org/api/grants.csv) was analysed to understand different trends. All the funding organizations were considered for the analysis. 

### Challenges - 
- Classification of grants to particular sectors. Though platforms are available which can help us to find the sector in which recipient organization works in, only 40% of records could have been classified with that methodology. 
- Time - Given the scope of dataset and time, Lack of time to build and train a classifier.

### Approach - 
The initial question can be disseminated into two parts. "Who has funded?" and "what themes throughout the years?" As the timeline is based on year and not months. The data can be summarised by years. The first question(who has funded) is easier to answer. A simple grouping of data based on funders name can help compile data. The challenging part was to identify the themes. After going through a couple of APIs and platform available, getting missing value data for theme classification seemed fundamentally difficult, due to lack of uniformity and availability, Thus text analysis methodology using NLP algorithms was needed to extract important keywords from grants to identify themes. 

### Methodology : 
- Analysed and assessed the dataset. Given that many parameters had different proportions of missing values. 
- Extracted Keywords from each record using Grant Title name and Grant Description. 
- Complied, grouped and indexed data by Funding Organization Name and Years of Funding. 
- Refined the keywords through another intervention to weed out outlier(keywords which dont make sense).
- Designed visualization using D3. 

### Caveats - 
The keywords are specific in nature and may/maynot point to a larger sector in general. While some may be very specific and dont need any context, some may point to a bigger cause without the specificity. Though the question doesnt ask specifically of how much each theme was funded by an organization in a year, the correct visualisation has a lack of provision to answer that question  

#####  Note : Data Preparation and Analysis Scripts would be published soon! 
