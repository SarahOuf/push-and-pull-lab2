# push-and-pull-lab2

### Backend Directory
- /backend/index.js has the routes
    * while running the users socketIds will be printed in the terminal.

### Frontend Directory
- /src/WebSockets.jsx component has the task for sending a broadcast message and sending to a specific user using socketID.
    * while running the task to send a broadcast message, just enter a message in the message field.
    * to send to a specific user, copy the user's socketId from the backend terminal and paste it in the userId field and hit enter then send a message as normal.
- /src/WebSocketsRooms.jsx component has the task for sending a message to a specifced room.
    * while running enter the group name you want the user to subscribe to and hit enter.
    * then send the message as normal.
- To run the WebSocketsRooms in the /src/index.js uncomment the line for importing WebSocketsRooms.jsx and uncomment the component in ReactDOM.render().
