# API Advanced

This project covers various advanced topics related to working with APIs, including reading API documentation, using pagination, parsing JSON results, making recursive API calls, and sorting dictionaries by value.

## General

To understand and work with APIs effectively, it's essential to follow these general guidelines:

- Start by carefully reading the API documentation provided by the service you are working with. Look for sections or documentation pages related to endpoints or resources.
- Pay attention to the authentication requirements, request headers, and response formats specified in the documentation.
- Take note of the base URL and any specific path or query parameters needed for each endpoint.

## How to Read API Documentation to Find the Endpoints You're Looking For

To find the endpoints you're looking for in an API documentation:

- Review the API documentation thoroughly, looking for sections or pages related to endpoints or resources.
- Understand the purpose of each endpoint and the required parameters.
- Take note of the base URL and any specific path or query parameters needed for each endpoint.

## How to Use an API with Pagination

To work with an API that supports pagination:

- Check the API documentation for information about pagination, including parameters such as `page`, `limit`, or `offset`.
- Make an initial request to the API to retrieve the first page of results.
- Extract the relevant data from the response and process it as needed.
- Check if there are additional pages by examining the response headers or data.
- If more pages exist, construct the next request with the appropriate pagination parameters and repeat the process until all data is retrieved.

## How to Parse JSON Results from an API

To parse JSON results obtained from an API:

- After making an API request, examine the response content to determine its format.
- If the response is in JSON format, use the `json` module in Python to parse the JSON response into a Python data structure (e.g., a dictionary or a list).
- Once parsed, you can access the data using standard dictionary or list operations.

## How to Make a Recursive API Call

To make a recursive API call:

- Define a recursive function that takes the necessary parameters to make an API request.
- Within the function, make the API request and process the response.
- If there is more data to retrieve or traverse, call the function recursively with the appropriate parameters.
- Combine the results obtained in each recursive call and return the final result.

## How to Sort a Dictionary by Value

To sort a dictionary by value:

- Use the `sorted()` function in Python.
- Pass the dictionary as the first argument to `sorted()`.
- Use the `key` parameter to specify the function that extracts the value for sorting.
- Assign the sorted result back to a dictionary or convert it to a list of tuples if necessary.

## Requirements

- Allowed editors: vi, vim, emacs
- All files will be interpreted/compiled on Ubuntu 14.04 LTS using Python 3.4.3
- All files should end with a new line
- The first line of all files should be exactly `#!/usr/bin/python3`
- Libraries imported in your Python files must be organized in alphabetical order
- A README.md file, at the root of the project folder, is mandatory
- Your code should use the PEP 8 style
- All files must be executable
- The length of your files will be tested using `wc`
- All modules should have documentation (run `python3 -c 'print(__import__("my_module").__doc__)'`)
- The Requests module should be used for sending HTTP requests to the Reddit API
