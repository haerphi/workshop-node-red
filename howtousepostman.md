# Welcome in the node-red workshop !

## Short postman intro

Postman is a software that help you to test your api.

## Test a GET (without paramaters)

- in the field next the `GET` just write the url of the api and click on `send` to do the request <br>
  ![helloGET](./postmanimg/getHello.png)

  other example where I want to get all todos
  ![getTodos](./postmanimg/getTodos.png)

## Test a GET (with paramaters)

- in the field next the `GET` just write the url of the api, add a `/` and a value and click on `send` to do the request. <br>
  In this example, I'm looking for a particular task. <br>
  ![getTodoId](./postmanimg/getTodoId.png)

## Test a POST

- in the headers tab, you will need to insert a new line : `Content-Type` and `application/json`. It means : "you will send information in JSON". <br>
  ![headers](./postmanimg/headers.png)

(don't worry if the url of the request change, I just change my mind when I did the screenshot)

- in the body tab, you will need to check the `row` circle and write few line of JSON like the example <br>
  ![body](./postmanimg/body.png)
