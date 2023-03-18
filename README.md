# Website_scraping-analysis
Module 11

Please see the attached documents which include code and created csv file.

This challenge was to demonstrate web-scraping and data analysis by extracting information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. This includes scraping various types of information such as HTML tables and recurring elements, like multiple news articles on a webpage.

## Part 1
### Scrape titles and preview text from Mars news articles.

Using splinter and beautiful soup to scrape the mars news website to extract the news titles and their article previews.

![title+preview](https://user-images.githubusercontent.com/120147552/225094347-09f81829-5d90-454e-8112-ab7c7e2d78c3.png)

## Part 2
### Scrape and analyze Mars weather data, which exists in a table.

Assemble the scraped data into a Pandas DataFrame

![pd](https://user-images.githubusercontent.com/120147552/225095795-c07f9f54-cfe4-4ee7-939f-b704d6f7185c.png)

Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.Below are the columns converted to appropriate types.

![updated types](https://user-images.githubusercontent.com/120147552/225096245-7bc2fc5d-ddc7-4e9b-872a-c3d52269b4be.png)

What are the coldest and the warmest months on Mars (at the location of Curiosity)? Plot the results as a bar chart.
*  The coldest months are [3, 4] and the hottest months are [8, 9].

![temp](https://user-images.githubusercontent.com/120147552/225097782-003003c8-c79e-435a-8c5f-628e78baa0b5.png)

Which months have the lowest and the highest atmospheric pressure on Mars? Plot the results as a bar chart.
*  The months with the lowest pressure are [6, 5] and the months with the highest pressure are [9, 2]

![pressure](https://user-images.githubusercontent.com/120147552/225098359-395b4bf2-a421-458e-a627-aee2bfc51b9b.png)

About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
Consider how many days elapse on Earth in the time that Mars circles the Sun once.
Visually estimate the result by plotting the daily minimum temperature.
* There are approximately 668/669 Earth days in 1 Mars year. Google search confirms that a Mars year is equivalent to 687 earth days.

![days](https://user-images.githubusercontent.com/120147552/225098671-d1603075-1eb6-4dac-8fe2-c1c75893b308.png)

DataFrame exported as a csv file.

![csv](https://user-images.githubusercontent.com/120147552/225099158-2eb8ef9b-3281-4f35-8ba3-e7d836ba123e.png)
