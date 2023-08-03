
# WorldXplorer
This is a web application for hotel & resort booking.

![Light](https://github.com/siddhantdixit/WorldXplorer/assets/22856752/2cb423ea-e7b9-46cd-8cbd-ee5561d363c0)

### Built With
* [React](https://reactjs.org/)
* [Node JS](https://nodejs.org/en/)
* [Express JS](https://expressjs.com/)
* [GraphQL](https://graphql.org/)
* [MongoDB](https://www.mongodb.com/)



## Installation

1. Clone the repository:


2. Navigate to the project folder.

3. Make sure you have MongoDB installed and running.

4. Create a new database collection for the web app.

5. Copy the connection URL for the MongoDB database.

6. Navigate to the `server` folder:

    ```
    cd server
    ```

7. Create a new `.env` file in the `server` folder.

8. Inside the `.env` file, add the following line with the connection URL you copied:

    ```
    MONGO_URL=<paste-your-connection-url-here>
    ```



9. Save the `.env` file.

10. Install the server dependencies:
    ```
    npm install
    ```

11. Start the server:
    ```
    npm server.js
    ```

12. Open a new terminal.

13. Navigate to the `client` folder:
    ```
    cd client
    ```

14. Install the client dependencies:
    ```
    npm install
    ```

15. Start the client:
    ```
    npm start
    ```

Now, you should have the WorldXplorer up and running. The server should be running on one terminal, and the client should be running on another terminal. Access the app by opening a web browser and visiting `http://localhost:3000`.
