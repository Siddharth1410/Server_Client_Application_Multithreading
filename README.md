# Server_Client_Application_Multithreading
Server Client Application made in Python using Multithreading
## Running Instruction 
### How to run server on terminal:
	Go to the server.py directory 
	type python Server.py 
		The Server starts running and waits for client connection 

### How to run Client on terminal:
	Go to the client.py directory
	type python Client.py 127.0.0.1 8112 helloWorld.html -> This gives the data on the client side 
		or
	type python Client.py 127.0.0.1 8112 someOtherFile.html -> This gives the 404 Not Found Error on Client side 

### How to run on browser:
	Go to the server.py directory 
	type python Server.py 
		The Server starts running and waits for client connection 

### Open a browser, and type:
		http://localhost:8112/helloWorld.html -> This prints HelloWorld on the screen 
			or
		http://localhost:8112/someOtherfile.html -> This gives the 404 Not Found Error on Client side 
		
## Example Output
### Server on Terminal
<img width="644" alt="Server on Terminal" src="https://user-images.githubusercontent.com/28666943/83085028-91ef8a00-a03f-11ea-9a13-03a976681fc9.png">

### Client on Terminal

<img width="885" alt="Running Client on Terminal" src="https://user-images.githubusercontent.com/28666943/83085095-c4998280-a03f-11ea-893a-1ebd4ad652bf.png">


### Client on Browser

![Client Browser](https://user-images.githubusercontent.com/28666943/83085101-c82d0980-a03f-11ea-9d53-da67af50fc0a.png)
