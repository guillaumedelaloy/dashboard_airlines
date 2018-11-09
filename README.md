# dashboard_airlines
This is an interactive dashboard using **API Gateway as proxy for DynamoDB**.
<br><br><br>
The dynamo table has been built in the project airlines-complaints.
It contains tweets of complaints for 3 different airline companies. The tweets have been classified in different topics (luggage issue, late flights etc...) from 2nd of November to 7th of November. 
<br><br><br>
**How does it work?**
<br><br>
**1:** Choose a company from the drop down list.
<br>
**2:** Click "upload data", this will call the data from the Dynamo table thanks to API Gateway.
<br>
**3:** Click "plot viz" to display the graph
<br>

Thanks to this dashboard, **you can visualize the different types of complaints per company.** 
<br>
**Hover and click the topics' names in order to filter.**


<br>
<br>
**website hosted on S3 [here](https://s3.amazonaws.com/dynamo-in-browser/index.html)**
