# Instant-Message-System-Design
The team implemented a client application with a simple UI that support instant messaging among different users. Our application allows new users to register an account by input a username, password, and confirmation password. An existing user can login to our application by put in his username and password. The system will check if such user exists or not; if the user exists, he will be able to access all the features, if the user does not exist, a “No such user” dialog will appear in the login page to indicate a failure of login.
In the main system, the user has a friend-list that shows all his friends, a block-list shows all the people he has blocked, a message field shows his messages with the other users, a text field that allows the user to text and send message. When the user clicks a specific friend in his friend-list, he is able to view all the messages he has with this friend in the message field. In order to send message to a specific friend, the user needs to click a specific friend in his friend-list, then type the message in the text field and send to his friend. In our current implementation, the friend that the user wants to talk to needs to be on-line as well, otherwise, the message won't be received when his friend logs into the system later on. This is done because of the data storage system we currently have. There's also a Add Friend List button that allows user to add someone to his friend-list. The user needs to input the person's username in order to add that person to the friend-list. Similarly, there’s an Add Block List button that allows user to block someone. Again, the username is needed for the person to be blocked. The user can only talk to his friend if they are mutually on each other’s friend-list. If a user is on a person’s block-list, he would not be able to talk to that person, and a message would be displayed to indicate that he is on that person’s block-list.
There’s also a Choose A Chat Room button that allows user to create or join a Chatroom in which he can communicate with other users publically. When this button is clicked, the user needs to input the Chatroom’s name in order to join that Chatroom. A user can access to multiple Chatrooms at the same time.
