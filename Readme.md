<h1>RealTime Chat Application </h1>

<ul>
<li>It is an scalable Realtime Chatting Application that provides an interface for multiple user chatting at the same time.</li>
<li>FrontEnd Technologies- React + Vite </li>
<li>BackEnd Technologies- Node.js, Express.js</li>
<li>Used Socket.io module for a two-way connection between client and server.</li>
<li>Added Client sided JavaScript for the purpose of playing with DOM elements.</li>
<li>First of all stored all the DOM elements in a respectives JS variable.</li>
<li>Used Audio file  which gives notification on receiving the messages.</li>
<li>Everytime a new user tries to join, first of all ask his/her name and chat room number.</li>
<li>If a new user joins, receive the event from the server using eventListner.</li>
<li>Receive message from server using 
<li>Server Side JavaScript will handle the Socket IO connections.</li>
<li>If a new user joins, let the other users connected with server know.</li>
<li>If someone sends the message, broadcast it to other people.</li>

</ul>

# Process to run the app
<ol>
  <li> go to server and run <b>nodemon server.js</b>
  <li> go to client and write on terminal <b>npm run dev</b>
  <li> A instance of the application will appear in the browser. 
  <li> Copy the url from the address bar and open another instance in another tab or in incognito or on another browser.
</ol>

# Screenshots

![Screenshot1](https://github.com/manishh12/Chat_app_assign/blob/main/screenshot4.png "User login")

![Screenshot2](https://github.com/manishh12/Chat_app_assign/blob/main/screenshot3.png "User inside room")

![Screenshot3](https://github.com/manishh12/Chat_app_assign/blob/main/screenshot2.png "another user")

![Screenshot4](https://github.com/manishh12/Chat_app_assign/blob/main/screenshot1.png "User UI")