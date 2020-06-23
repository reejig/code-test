# code-test
This is a test for full stack developer.

# Description
Given data from https://s3-ap-southeast-2.amazonaws.com/reejig.com/code-test/data.json, create a search function to allow user to search contacts by name/gender/city.

# Acceptence Criteria
* Create backend with Laravel http-client to consume the JSON file
* Populate the contact current_company and current_job_title in the contact root object from the contact.experiences object. (There are multiple experience items. Please find the latest experience and assign the value to current_company/current_job_title.)
* Create a search API to accept search terms for name/gender/city and return the contact results in JSON. (Remove the contact.experiences from returned JSON)

* Create a frontend with VueJS with a search box to allow search 3 fields: Name, Gender and City.
* Display the search results in a table with fields: First Name, Last Name, Current Job Title, Current Company, Gender, City.

# Bonus Points
* Add a sorting feature
* Use docker
* Use Element UI
