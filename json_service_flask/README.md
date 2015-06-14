#Json Service 

###Preperation
Install the required packages:

```pip install Flask```

###Description
During hackathons we are commonly required to build some RESTful application I worked this together for **future** hackathons in order to make deploying back ends faster and easier.

###How to use

| HTTP Verb        | Action           | Ex  |
| ------------- |:-------------:| -----:|
| GET      | request json data from the list of elements in the db  | http://localhost/tasks |
| GET      | request a single element       | http://localhost/tasks/id |
| POST | add a element to the list    |  http://localhost/tasks   |
