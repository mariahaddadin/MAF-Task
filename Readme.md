# Testing University List APIs (QA Challenge)


For this, you're going to need Postman. We have a collection with API requests and tests for each request.

To see the results, import the following file in your Postman
```
List of Universities.postman_collection.json
```


### Test Cases:
1. Validate third party is able to view all universities with correct corresponding data when leaving search criteria empty
2. Validate third party is able to search for universities by name and matched university to appear on the list
3. Validate no data is displayed when using invalid "name" as search criteria
4. Validate third party is able to search for universities by country and matched universities to appear on the list
5. Validate no data is displayed when using invalid "country" as search criteria
6. Validate third party is able to search for universities by a correct combination of valid name AND valid country, and matched universities to appear on the list
7. Validate no data is displayed for the third party when using combination of valid name and invalid country
8. Validate no data is displayed for the third party when using combination of invalid name and valid country
9. Validate no data is displayed for the third party when using combination of name and country unrelated to each other
