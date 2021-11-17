# UFOs
Use JavaScript to add dynamic elements to a webpage

# Purpose
The aim of this analysis is to create a webpage with a dynamic table which has the ability to filter data about UFO sightings based on date, location and shape.

# Results
Wheen the page loads, it automatically loads information from the "data.js" file. But, we were able to successfully implement the use of filters to yield results based on date, location and shape.

In the example below, we filtered sightings in Californnia as on 01/01/2010 which yielded the following results:

![alt text](https://github.com/anamahmed15/UFOs/blob/main/Static/images/Filtered_table.png)

# Summary
This is a great solution, however we have to be careful as the text inputs are case sensitive (as per javascript syntax). For instance, if someone typed 'CA' instead of 'ca' under location, they made not yield any results.

Also, another drawback to note is that the table will provide results for a perfect match of a word or date. For instance, if we type 'c' under location, the table won't yiedl results of all states starting with 'a' but will look for a state named 'a' providing an empty table.



