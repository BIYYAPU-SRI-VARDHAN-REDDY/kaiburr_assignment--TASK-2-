# kaiburr_assignment--TASK-2-
Task 2. Swagger codegen.
Create the same REST API as in task #1, but use https://editor.swagger.io/ to create your API
definition and generate the server code. Choose any java-based server or server framework,
that you like. You can either use the online editor or generate the code manually, e.g. using this
document: https://github.com/swagger-api/swagger-codegen/wiki/server-stub-generator-howto.
Make sure that you can deploy/run the generated code. Once your stub is ready - implement the
same functionality as described in task #1, but now in java.
Finally, be sure that you can show how your application responds to requests using postman,
curl or any other HTTP client.

# steps for solution
Step 1: Create the API definition in Swagger Editor
Go to https://editor.swagger.io/ and create a new API definition. Use the YAML code given above as a starting point

This API definition defines four endpoints for getting all servers, adding a new server, getting a server by ID, and deleting a server by ID. It also defines a model for the Server object.

Step 2: Generate the server code using Swagger Codegen
Go to https://editor.swagger.io/ and click on "Generate Server" in the top menu. Choose the Java language and the server framework you want to use. You can choose from various frameworks such as Spring Boot, Vert.x, Jersey, and more.

Once you have selected the framework, click on "Download" to download the generated code.

Step 3: Implement the API functionality
Open the generated code in your favorite IDE and implement the API functionality. You can use the code from Task #1 as a reference. Make sure that the endpoints and models match the ones defined in the API definition.

Step 4: Run the server and test the API
Run the server and test the API using Postman, curl or any other HTTP client. Make sure that the API
