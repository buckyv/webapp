# webapp

Sample web app that you can hit from local host to get users info. 

### Further tasks
* Create two endpoints 
   ** POST call: `/create?name={name}&surname={surname}` creates a user with name - `{name}`, and surname - `{surname}`. This user should be persisted in any database of your choice, MYSQL or NOSQL. Write instructions to set the DB for your project. Primary key - `name`, for now names will be unique.

   ** GET Call: `/get?name={name}` retrieves information about the user with name `{name}`