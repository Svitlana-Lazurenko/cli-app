# CLI-app

A CLI-application that works with a database in JSON format.

## Commands

### We receive and display the entire list of contacts in the form of a table

- node index.js --action="list"
- result:

![CLI-app. Screenshot.](/screenshots/1.png)

### We get a contact by id and output the contact object or null to the console, if there is no contact with such an id.

- node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6
- result:

![CLI-app. Screenshot.](/screenshots/2.png)

### We add a contact and display the object of the newly created contact in the console

- node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22
- result:

![CLI-app. Screenshot.](/screenshots/3.png)

### We delete the contact and display the object of the deleted contact or null in the console, if the contact with this id does not exist.

- node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH
- result:

![CLI-app. Screenshot.](/screenshots/4.png)
