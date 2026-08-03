Volera E-Commerce API Testing

About the Project

I made this project to practice API testing using Postman.

I used an e-commerce API and tested different requests such as login, getting products, searching for products, updating a product, and deleting a product.

Tools I Used

- Postman
- REST API
- JSON
- JavaScript for Postman tests

What I Tested

- Login
- Get products
- Search for a product
- Get a single product
- Update a product
- Delete a product

For the responses, I checked status codes and important data returned by the API.

Environment Variables

I created a Postman environment called "ShopEase QA Environment".

I used variables such as:

- "baseUrl"
- "accessToken"

The "baseUrl" stores the API URL, so I can reuse it in different requests.

After login, I also extracted the access token from the response and stored it as an environment variable.

Tests

I added basic JavaScript tests in Postman to check whether the requests returned the expected results.

For example, I checked status codes and whether important values were present in the response.

Collection Runner

I used Postman's Collection Runner to run my requests together instead of running every request separately.

What I Learned

Through this project, I learned how to:

- Send API requests using Postman
- Work with GET, POST, PUT and DELETE methods
- Work with JSON data
- Use Postman variables and environments
- Extract values from API responses
- Write basic API tests
- Organize requests into a collection
- Run multiple API tests using Collection Runner

API Used

I used DummyJSON for this project. It provides sample data and APIs that can be used for testing and learning.

Project Goal

My goal was to get hands-on practice with API testing and understand how Postman can be used to test API requests and automate basic checks.
