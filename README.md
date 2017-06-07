# express-cookies-sessions
* Using of cookies for authentication. The server will send a signed cookie to the client upon   successful authentication, and expects the client to include the cookie with every         subsequent request.       
- Set up your Express application to send signed cookies.
- Set up your Express application to parse the cookies in the header of the incoming request     messages
# Using cookie-parser
- Install the cookie-parser Express middleware in your basic-auth folder by typing the     following at the prompt:
````
     npm install cookie-parser --save
````
* Using Express sessions to track authenticated users so as to enable authenticated access to server resources.
  - Set up your Express server to use Express sessions to track authenticated users
  - Enable clients to access secure resources on the server after authentication.
# Installing express-session
  - Install express-session and session-file-store Node modules as follows:
````
     npm install express-session session-file-store --save
````

