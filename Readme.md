A basic server and client using sockets
	- Himanshu Maheshwari(20171033)

This is basic server and client model. They both can communicate by establishing socket connections. The client can ask for information about all the files in server's directory using 'listall' command. Then it can also ask to send a specific file using 'send <file_name>' command. Clien can close the connection using 'close' command. This model support multiple clients. The code has been wrtten in c, and only socket programming is used and no other external library is used. Errors are handled gracefully.

How to run:
1) Server
	a) First compile 'server.c' using 'gcc server.c' command in terminal.
	b) Next run the file using './a.out' command. Server would be then set up.

2) Client
	a) First compile 'client.c' using 'gcc client.c' command in terminal. The client and sever files could be in seperate directories.
	b) Next run the file using './a.out' command. Client would then be connected to server if the server is running, otherwise it would show an error message.
	c) Multiple clients could run simultaneously. 
