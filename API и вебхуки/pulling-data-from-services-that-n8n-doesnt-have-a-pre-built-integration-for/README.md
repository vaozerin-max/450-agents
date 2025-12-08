

This workflow demonstrates various use cases of the HTTP Request node, including data scraping, splitting response data into items, and handling pagination.

Example: A user might use this workflow to fetch a list of their starred GitHub repositories, extract the titles of recent blog posts, and split a JSON response into individual items for further processing.

## What You Can Do
- Data Scraping: The workflow fetches a random Wikipedia page and extracts the article title using the HTML Extract node.
- Splitting Response Data: The workflow takes the response body from an HTTP Request and splits it into individual items using the Item Lists node.
- Handling Pagination: The workflow demonstrates how to loop through paginated data from the GitHub API, incrementing the page number after each request.

