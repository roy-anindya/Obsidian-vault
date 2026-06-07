
![[Pasted image 20260601223852.png]]

ABAP Application layer mainly consists of four Major Components:

1. **Dispatcher**: All The requests that are coming from the application layer are intercepted by the dispatcher and the dispatcher will store all these requests into the Dispatcher Queue.
	- One by one this dispatcher will allocates these available requests into First Avilable Work Process.

2. **Work Process**: Work process is the brain of the application Layer. Work Process handles the requests coming from the Dispatcher. 
	- Work Process can only Handle One Request at a time
3. **User Context**: Temporary Memory Available on the Application Layer who is responsible for storing User data.
	- When We Log In to our SAP system, our data will be stored into this user context memory and when we will logout our Data will be freed.
4. **Roll Area**: Roll Area is the Temporary Memory on the Application LAyer.
	- When the program is Executed at that time a roll is allocated for the program, and when the program execution will be finished, the roll area will be freed. 
	- Roll Area calculates the data, comparing with the database and perform executions and provide output to the dispatcher, and ultimately to Presentation server.


