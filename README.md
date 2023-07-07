# fairos-access-token-display
This project displays the access token of an user, given a fairos-dfs server url, username and password.

Clone this repo, open the `index.html` page. Then put your fairOS-dfs server url along with username and password.

A successful login will display the user accessToken. This access token is session based. So having accessToken generated from one server will not work on another server, even it will not work is the server is restarted. The token will expire after 24 hours. 
