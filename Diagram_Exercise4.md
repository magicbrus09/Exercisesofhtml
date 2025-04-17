sequenceDiagram
  participant user
  participant server
Note right of user: The user writes its message and presses the "Send" button
user->>HTTPS POST: (user's msg)
activate server
server->>Force
