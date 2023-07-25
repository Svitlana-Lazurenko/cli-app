================COMMANDS AND THE RESULTS OF THEIR EXECUTION================

# We receive and display the entire list of contacts in the form of a table

node index.js --action="list" ------ A link with a screenshot of the execution result: https://drive.google.com/file/d/18wWj8shfB0fhaiTirjb7e6ehwm9plT7_/view?usp=drive_link

# We get a contact by id and output the contact object or null to the console, if there is no contact with such an id.

node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6 ------ A link with a screenshot of the execution result: https://drive.google.com/file/d/1GRHO2A_YEjZyxiGkWoQy7mQNEDdSTnhR/view?usp=drive_link

# We add a contact and display the object of the newly created contact in the console

node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22 ------ A link with a screenshot of the execution result: https://drive.google.com/file/d/1tFJ8_hPWkP1liQLT1KF3oF32oWdlMgzA/view?usp=drive_link

# We delete the contact and display the object of the deleted contact or null in the console, if the contact with this id does not exist.

node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH ------ A link with a screenshot of the execution result: https://drive.google.com/file/d/1Cco9GI-oTl3ctv7X22j1lHBXZe6D4P5Z/view?usp=drive_link
