# Server-Client

Updating project to protect against plagiarism and to protect the data that was used.
Please check back soon.

Purpose: 
- The purpose of this code is to simulate a client-server relationship.
- File 1: The client may pass the server any string and the server will return a capitalized version of the string.
- File 2: Once logged in with correct credentials, may add or remove from a queue and print the results.

How to run File 1:
- Download code.
- Open Command Prompt or equivalent terminal.
- Navigate to folder where code is saved.
- Start the server: java ServerName
- Make note of the PortNumber.
- Start the client: java ClientName localhost 'PortNumber'.
- Submit text to be converted to uppercase on client side. 'EXIT' to disconnect.

How to run File 2:
- Download code.
- Open Command Prompt or equivalent terminal.
- Navigate to folder where code is saved.
- Start the server: java ServerName
- Make note of the PortNumber.
- Start the client: java ClientName localhost 'PortNumber'.
- Enter username: username.
- Enter password: password.
- Add items to a queue with command 'add x', where x is the desired item to add.
- Remove items from the queue with command 'remove'. Removes the first item in the queue.
- Print queue with command 'print'.
