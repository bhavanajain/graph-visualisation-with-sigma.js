# graph-visualisation-with-sigma.js
Graph visualisation using Javascript library (sigma.js) and using No-SQL graph database Neo4j -  A demo movie database with movies , actors , directors and other crew persons related to each movie ( from neo4j sample databases ). Along with graph visualisation , we added interaction with it . So , a person could create an account , mark movies as watched , follow an actor and rate a movie as well .

To run this project , you need to -

1)Install neo4j web browser from  “http://neo4j.com/download/”

2)To run neo4j
 	--- cd to the extracted folder
	--- type command - “sudo bin/neo4j start”
It should start the neo4j server on “http://localhost:7474/”

3)Now , in the query interface run the query provided in file named - “neo4jquery.txt”

4)Now, Just clone the folder and just run a simple server to get started. I prefer the python module, ```python -m SimpleHTTPServer```
This should get a local server running on 8000 port .

5)Change the neo4j username and password , to your username and password in the files – index.html and register.html under the examples folder .
In the files uploaded – username and password is “bhavana” .

6)In the browser , go to “http://localhost:8000/register.html” to enroll as new user and “http://localhost:8000/index.html” to see the interface
