# Server Connected to Mongodb

-->First we need to created a cluster in mongodb atlas.

-->  Install Express `npm i express ` & Mongoose `npm i mongoose`.

-->And require Middleware without middleware we can't get requests and responses.

//Schema

-->When connecting to a database, a schema refers to a logical blueprint that defines how data is organized within the database. It's essentially a set of rules that govern the structure of your data.
Check the models page for this breif clarification.

-->Here are some common server-side operations to `req & res` get the data from mongodb DataBase side.

##CRUD operations on Tasks: =>` POST // GET // PUT // DELETE `

 -->Create: This allows users to add new tasks to their list. The server receives the task details (title, description, etc.) via a POST request and stores them in a database or persistent storage.

 -->Read: This retrieves tasks from the server. Users can:
 
1.Get all tasks: This sends a GET request to fetch the entire list.
2.Get specific tasks: This involves sending a GET request with filters (e.g., by ID, completed status) to retrieve specific tasks.

-->Update: This allows modifying existing tasks. A PUT or PATCH request is sent with the updated information (e.g., changing title, marking a task complete).

-->Delete: Users can remove tasks. This involves sending a DELETE request with the task ID to remove it from the server.

##=>For Breif clarification to check the Server.js File.



