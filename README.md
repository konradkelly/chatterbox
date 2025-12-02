# chatterbox

An assignment to explore sockets and multithreading. MAKE SURE TO COMMIT AND PUSH AS YOU GO. YOU SHOULD BE MAKING MULTIPLE COMMITS PER WAVE.

## Wave 1: Understand
1. Take a moment to read through the ChatterboxClient.java file. Note what is currently implemented, and what you will be expected to implement.
1. Try running ChatterboxServer using the example command in ChatterboxServer.java. You dod not need to understand everything in this file, but you will be using the server to validate that your client is working!
1. Try running ChatterboxClient using the command in the file. It will tell you that argument parsing is not yet implemented (because you haven't written it yet!) This is expected

## Wave 2: Argument Parsing
1. Implement `parseArgs` according to the instructions.
1. Validate your solution by re-running the client. Make sure everything is parsed correctly! It should now give you an error about the next wave. Make sure it properly handles invalid input too.
1. Make sure you've committed and pushed!


## Wave 3: Client Constructor
1. Implement the ChatterboxClient constructor. You will note it is already partially created for you.
1. Validate your solution by re-running the client. It should now give you an error about the next wave.
1. Make sure you've committed and pushed!

## Wave 4: Connect
1. Implement the connect method.
1. MAKE SURE THE SERVER IS RUNNING.
1. Validate your solution by re-running the client. Make sure to use localhost and the same port the server is on. It should now give you an error about the next wave.
1. Make sure you've committed and pushed!

## Wave 5: Authenticate
1. Implement the authenticate method. Your client will need to send the username and password, separated by a space and ended with a newline.
1. MAKE SURE THE SERVER IS RUNNING.
1. Validate your solution by re-running the client. Make sure to use localhost and the same port the server is on. It should now give you an error about the next wave.
1. Make sure you've committed and pushed!

## Wave 6: Print Incoming
1. Implement `printIncomingChats` and call it in `streamChats`. Do not yet worry about threading or outgoing chats.
1. MAKE SURE THE SERVER IS RUNNING.
1. Validate your solution by re-running the client. Make sure to use localhost and the same port the server is on.
1. You should see a repeated heartbeat message from the server when it is working.
1. Make sure you've committed and pushed!

## Wave 7: Send Outgoing
1. Implement `sendOutgoingChats`. Modify `streamChats` so that it properly multithreads between printing incoming and sending outgoing.
1. MAKE SURE THE SERVER IS RUNNING.
1. Validate your solution by re-running the client. Make sure to use localhost and the same port the server is on.
1. Try connecting multiple clients! You'll need to use different usernames/passwords from sample_users.txt
1. Make sure you've committed and pushed.

## Wave 8: Connecting over the internet
1. You will be emailed a set of usernames and passwords to use for connecting to our live class server. DO NOT SHARE THESE PASSWORDS WITH ANYONE AND DO NOT COMMIT THEM TO YOUR REPOSITORY.

