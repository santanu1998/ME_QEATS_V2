
# QEats

### QEats is a popular food ordering app that allows users to browse and order their favorite dishes from nearby restaurants.

#### During the course of this project,

1. I had build different parts of the QEats backend which is a Spring Boot application.

2. Several REST API endpoints were implemented to query restaurant information and place food orders.

3. To give a sense of real-world problems, production issues were investigated using Scientific Debugging methods.

4. Along with this, I improved the app performance under large load scenarios as well as included an advanced search feature in the app.


### Image


![QEats](https://user-images.githubusercontent.com/69622683/227975156-28df2391-2d16-4b97-89e3-af8829651b8e.png)


## Retrieve restaurant data for a given user location

### Scope of Work

1. Implemented GET /API/v1/restaurants and the corresponding request handler and response methods.

2. Used Mockito to enable the development of the relevant MVCS layers independently.

3. Retrieved a list of restaurants from MongoDB based on a user location.

### Skills used
Spring Boot, Spring Data, REST API, Jackson, Mockito, JUnit, MongoDB


### Image(s)


![QEats1](https://user-images.githubusercontent.com/69622683/227975716-b62a5f40-32d0-4b69-913c-de9876207c2c.png)


## Resolve production issues using Scientific Debugging

### Scope of Work

1. Debug QEats app crashes from backend leveraging log messages and structured debugging techniques.

2. Use IDE features (breakpoints) and assert statements to identify the root cause.


### Skills used
Scientific Debugging



## Replicate performance issues and solve them using caching strategies

### Scope of Work

1. Employed JMeter or load testing to expose performance issues.

2. Identified DB queries contributing to degradation in performance.

3. Used a Redis cache to alleviate read performance.


### Skills used
Redis, JMeter



## Replicate performance issues and solve them using caching strategies

### Scope of Work

1. Employed JMeter or load testing to expose performance issues.

2. Identified DB queries contributing to degradation in performance.

3. Used a Redis cache to alleviate read performance.


### Skills used
Redis, JMeter


### Image(s)


https://user-images.githubusercontent.com/69622683/227976596-4bcaf4f9-f6eb-4aa5-9eb6-4510b136b859.mp4


## Perform search operations using custom attributes

### Scope of Work

1. Used MongoDB queries to enable users to search for restaurants using attributes like name, cuisine, dish, and price.

2. IUsed multithreading to increase the number of concurrent searches that can be performed.


### Skills used
MongoDB querying, Multithreading


### Image(s)


![QEats2](https://user-images.githubusercontent.com/69622683/227980955-789d49a1-a92b-4478-99c8-bf2dc83e1ba6.png)


![QEats3](https://user-images.githubusercontent.com/69622683/227981150-3019d1eb-1e15-430a-92cf-8a141f90336c.png)


![QEats4](https://user-images.githubusercontent.com/69622683/227981230-ac20b616-2a7f-4c9c-8d1f-8a5dbcb3bac4.png)



