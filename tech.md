# What happens after...
[when you type google.com into browser and press enter](https://github.com/alex/what-happens-when)

## HTTP / REST
[apigee](https://apigee.com/api-management/#/homepage)
[img](https://cdn.scotch.io/2826/H3bj3yikRyytQlfGRBY2_crud.png)

curl - a tool to transfer data from or to a server, using one of the supported protocols

REST - REpresentational State Transfer
Data presentation for a client in the format that is convenient for it. This is not a standard or protocol, this is an approach to or architectural style for writing API.

Client -> API <--> Database <- Database Data

CRUD: creating new data, receiving data in a convenient format, updating data, deleting data

HTTP method:
POST - creation
GET - receiving / getting
PUT - update (modification)
DELETE - removal

1xx - informational
2xx - success
3xx - redirection
4xx - client error
5xx - server error

## MVC
MVC = Model - View - Controller

Model <- Controller <--> Client (browser)
View <-> Controller

Model: maintains the relationship between object and database and handles validation, association, transactions

View: a presentation of data in a particular format, triggered by a controller's decision to present the data

Controller: the facility within the application that directs traffic, on the one hand querying the models for specific data, and on the other hand organizing that data (searching, sorting) into a form that fits the needs of a given view.

Browser <-> Web Server <-> Public --> Routing --> Controller

Web Server <---- View <-- Controller
Database <--> Model <---> Controller

**Rails:**
Active Record is the M in MVC - the model.

**Django**
1. React will consume your Django REST API. Front-ends and back-ends aren't connected in anyway. React will make HTTP requests to your REST API in order to fetch and set data.
2. React, with the help of Webpack (module bundler) & Babel (transpiler), will bundle and transpile your Javascript into single or multiple files that will be placed in the entry HTML page. Learn Webpack, Babel, Javascript and React and Redux (a state container). I believe you won't use Django templating but instead allow React to render the front-end.
3. As this page is rendered, React will consume the API to fetch data so React can render it. Your understanding of HTTP requests, Javascript (ES6), Promises, Middleware and React is essential here.

## Amazon
Amazon S3 : storage service
Amazon EC2 instance : remote computer running Windows or Linux, cloud web service solution
Amazon RDS for relational database
DynamoDB for NoSQL
