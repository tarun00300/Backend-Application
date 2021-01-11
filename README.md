# Backend-Application
## Instructions
Please stick to the following instructions on how to submit your application:
1. Read the whole README
2. Fork our repository
3. Add your solution to your repository
4. Create a pull request to our repository

Also note down in the end how many hours it took to complete (roughly). **Please do not spend more than 6 hours for the whole task.**

Thank you very much!

## Main Task
Develop a first version of the products module. Should be possible to fetch all the products, add a new one, delete it and edit existing ones. All the requirements are described in the mockup images and should be derived from it.
### Database View
![Database View](images/database_view.jpg)
### Create/Edit View
![Edit View](images/edit_view.jpg)

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
* Connect user object
    * GET :id should include the user object
      * make an api request to user api (https://jsonplaceholder.typicode.com/users/1)
    * the POST/PUT request will include a `userId`

## Bonus
The following points are optional but give additional credit:
* Caching
    * redis (or memcached)
* Test Coverage
* Get all should include the user object
* basic JWT Authentication
    * so only the owner of the object is allowed to edit / delete the product
* CORS functionality