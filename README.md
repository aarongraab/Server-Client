# Server-Client

Purpose: 
- The purpose of this code is to simulate a client-server relationship.
- UpperServer: The client may pass the server any string and the server will return a capitalized version of the string.
- QueueServer: Once logged in with correct credentials, may add or remove from a queue and print the results.

How to run UpperServer:
- Download code.
- Open Command Prompt or equivalent terminal.
- Navigate to folder where code is saved.
- Start the server: java UpperServer.
- Make note of the PortNumber.
- Start the client: java Client localhost 'PortNumber'.
- Submit text to be converted to uppercase on client side. 'EXIT' to disconnect.

How to run QueueServer:
- Download code.
- Open Command Prompt or equivalent terminal.
- Navigate to folder where code is saved.
- Start the server: java QueueServer.
- Make note of the PortNumber.
- Start the client: java Client localhost 'PortNumber'.
- Enter username: 'username'.
- Enter password: 'password'.
- If login attempt fails 5 times, server will disconnect.
- Add items to a queue with command 'add x', where x is the desired item to add.
- Remove items from the queue with command 'remove'. Removes the first item in the queue.
- Print queue with command 'print'.
