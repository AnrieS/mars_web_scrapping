# mars_web_scrapping

Module 11 challenge required a full web-scrapping and data analysis to learn how to use html elements on a page and find the id and class attributes. Using Splinter, html parsing with Beautiful Soup, I learned how to scrape various types of information. These include html tables and recurring elements.
As for the challenge itself, part 1 was simple. It required me to scrape the html and use the inspect tools to find the attributes and the elements to execute the Beautiful Soup module. Finding the titles and preview elements and store them into lists and print into the notebook.
Part 2 was much the same, use the provided link to visit the website and use beautiful soup to read the html elements. After which I stored the html table into pandas with the following column headers; “id”, “terrestrial_date”, “sol”, “ls”, “month”, “min_temp”, and “pressure”. Next, the challenge required me to change the data types of the appropriate “datetime” “int” or “float” data types. The last step of part 2 was creating Pandas functions to answer the following questions questions: 
•	“How many months exist on Mars?”
•	“How many Martian (and not Earth) days worth of data exist in the scraped dataset?”
•	“Which months have the lowest and the highest atmospheric pressure on Mars?”
•	“About how many terrestrial (Earth) days exist in a Martian year?”

