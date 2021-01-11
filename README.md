# Backend-Application
## Main Task
Develop a first version of the products module. Should be possible to fetch all the products, add a new one, delete it and edit existing ones. All the requirements are described in the mockup images and should be derived from it.  

**Please do not spend more than 6 hours for the whole task.**

## Submitting
Please stick to the following instructions on how to submit your application:
1. Fork our repository
2. Add your solution to your repository
3. Create a pull request to our repository 

Please also note down in the end how many hours (max. 6) it took to complete (roughly).

Thank you very much!

## Technical Requirements
* Database Design
    * Using SQLite or MySQL
        - When using MySQL, please add instructions
* Whole controller setup: POST/DELETE/UPDATE/GET
* Docker setup
* Query params
    * Filtering f.e. product types
    * Pagination in GET all
* Use EF Core ORM
* Mapping (automapper)
* One unit test
* GET :id should include the user object
    * make an api request to user api (https://jsonplaceholder.typicode.com/users/1)

## Bonus
The following points are optional but give additional credit:
* Caching
    * redis (or memcached)
* Test Coverage
* Get all should include the user object
* basic JWT Authentication
    * so only the owner of the object is allowed to edit / delete the product
* CORS functionality