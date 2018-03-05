# rest-api
REST API with MVC architecture

#My App Name
Demo app

##REST API
List of basic routes:

**Route** | **HTTP** | **Descrition**
----------|----------|---------------
<span style = "color:red">/api/hello?name={name}</span>| GET | Print hello, {name} !

List of user routes:

**Route** | **HTTP** | **Descrition**
----------|----------|---------------
/api/users | GET | Get all the users
/api/users/:id | GET | Get a single user
/api/users | POST | Create a user
/api/users/:id | DELETE | Delete a user
/api/users/:id | PUT | Update a user with new info
/api/users/:id | PATCH | Update a user with specific new info

List of filter routes:

**Route** | **HTTP** | **Descrition**
----------|----------|---------------
/api/users?name="{name}" | GET | Get {name} match in users
/api/users?name="{na}" | GET | Get {na} like in users

##Usage
With only npm:



