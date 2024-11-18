Online Library System 

The designed application is an Online Library System, allowing multiple users to access a library with a popular selection of series, such as The Hunger Games, Sherlock Holmes, and The Lord of the Rings. Users can borrow, return, view, or search for book series. The interface for this application is a Command Line Interface (CLI), but it remains highly user-friendly, with the system guiding users through the available commands and functionalities. To maintain simplicity, only one series is available for each selection, but users are notified when a series is returned to the library.


Steps to run the application: 

1) Run the server side with the command: java ServerSide 99
     In this command above, I used 99 as the port for an example, the user can specify a different port
2) Run clients with the following command: java ClientSide localhost 99
3) Enter command out of the following for multiple clients: (view, borrow <book name>, return <book name>, search <search term>)
4) The core functionality consists of a client borrowing a book series, it will be unavailable to other users until the first client returns it
5) Additional functionality is the view command showcasing all the books in the library, and the search command which allows you to search the library for a specific book
