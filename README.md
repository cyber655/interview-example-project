Showcase (deployed on Google Kubernetes Engine (GKE)):
===

Currently disabled because of costs.
Will be enabled again when it is necessary.

Description:
===

This is just an example project to discuss some technologies for an interview.
There are many todos to improve this project. (See TODO section - not all todos listed there).

How to get started for development:
===

1. Prerequisites:
 - Java 17
 - Maven >= 3.8.7 (should also work with lower versions)
 - Node.JS v16.13.2 (should also work with lower versions)
 - Docker Desktop => 2.x.x.x (should also work with lower versions)


2. Starting the database:

```shell
cd backend
docker-compose up
```

3. Starting the backend:

```
mvn clean package
```
```
Open Intellij and jump to class: 

InterviewExampleProjectApplication.java 

and press the green start button on the left.
```

Hint: You can open http://localhost:4667/api/swagger-ui/index.html#/ for the REST swagger documentation.

4. Starting the frontend:

```
npm install
npm run start
```


TODO list:
===
1. Extend Github actions tagging pipeline to automatically deploy the project to a GKE cluster
2. Write much more tests especially for the frontend and the backend
3. More coming soon...
