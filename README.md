# UFO

![78a0ef001bc2a7ee09227d2611cc645952c6-945x300](https://user-images.githubusercontent.com/84881187/130137226-964b4e18-eb71-40ec-abfa-4811f85fb5a1.jpg)



## Project Overview
For this project, our client has asked us to modify a webpage and dynamic table so that it may provide more in-depth analysis of UFO sightings across multiple criteria at the same time. 

## Results

Upon opening the webpage, our client will see the title with a pictured background at the top. When we scroll down, we see the header and text our client asked us to include. Beneath that, we can see our filters and all the data in a dynamic table. Please see below for a screenshot of the 2nd section of the webpage:

![WebPage_2](https://user-images.githubusercontent.com/84881187/130135993-ac2524ab-926e-4ea3-a49c-6f28de06f8d7.PNG)


The initial web page provided 2 search criteria, with Filter buttons, allowing the user to filter based on either criteria. We refactored our HTML code, to remove the buttons so that once the user presses 'Enter' on their keyboard, the webpage will filter based on the total input criteria. Looking at our updated webpage, we can see that we have inluded 5 different filters to choose from for the data: Date, City, State, Country, and Shape. We modified the code, so that users can choose any of these filters, and the webpage will provide any and all data specific to the input search criteria. Please see below for examples of filtered searches:


*Search by single criterion:*

![Webpage_2_Search_1](https://user-images.githubusercontent.com/84881187/130136862-4bd2d780-d3dd-4db2-9f38-347e84424862.PNG)

*Search by multiple criterion:*

![Webpage_2_Search_2](https://user-images.githubusercontent.com/84881187/130136895-80843cf2-df81-48d4-9c00-92a9f731b4ac.PNG)

In the example above, we can see that but filling in multiple criteria, we can narrow dow our data from just instances occuring on 1/13/2010, to more specific criteria (occurences on 'Date' 1/13/2010, in 'City' white oak, in 'State' pa, in 'Country' us, in a triangle 'Shape'). You can fill all the criteria to fill your searches, or just a few to collect the data that you require. In the example screenshot below, we see that we have filter the data by Date (1//11/2010) and by Country (us), to give us filtered data for our needs. 

![WebPage_Search_3](https://user-images.githubusercontent.com/84881187/130156498-846d5783-b16c-4ddb-9a22-33272e0b3952.PNG)



## Project Summary

Per our client's request, we have created a clean and functional webpage to filter through different criteria and will display the filtered results on the webpage. This will greatly help provide a more in-depth analysis of the data provided. 

However, one big drawback with the filtered dynamic table database we have, is that our data is very prone to mis-input errors from the user end. Our code, directly parses through our data.js file. In our data file, all names and initials are input in lower case lettering. Any accidental inputs in letter casing could skew the data filtered. If one were to search for California using the abbreviation 'CA' vs 'ca' as noted in the data, there would be no results. See picture below for example:

![WebPage_Search_Error](https://user-images.githubusercontent.com/84881187/130167896-2c36f80d-b2f4-4a84-acf4-fb7fbe1b8bb0.PNG)


Our code does a great job filtering the data provided, but there are some recommendations I would make to improve the webpage. First off, is updating and collecting more data. Our data set is pretty outdated, and 10 years old. It would be beneifial to increase our sample size and collect more data. We could scrape some data from other sites collecting similar data, and we could also create another webpage or form where users can submit their own data to the page.

On the note of collecting more data, one recommendation I would add to our data set would be to incorporate the number of viewers in an instance. The nature of our data leads to increased skepticism in validity. We can minimize unreliable entries by collecting and filtering data on how many viewers were present during the sighting. This way data can also be filtered to exclude single viewer sightings if you wanted to.  

