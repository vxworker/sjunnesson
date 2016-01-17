# Introduction #

With this code you will be able to easily get up and running using twitter and processing. Just supply your own username and password and u will be able to easily experiment with the different functions.


# Details #

The code is put together of five different functions:


updateStatus(String); is sending a new Status update to your twitter account.

getAllUpdates(); returns all the Status updates from your twitter account. (hasnt been tested with many tweets just with 20 something...)

getlatestUpdate(); returns the latest published status update with the logged in account

getFriendsID(); returns all the IDs of friends connected to the user.

getFriendsStatus(int); returns the lastest statusupdate from the supplied int. This is built up in the way that the first added friend is 0 (zero) and then it counts upwards. Will give u a small error message if you are trying to retrieve a to high number.