# SpotifyPlunderer
Writes all of the artists in your spotify liked songs to a .txt file


### How To Use
To use, make a new spotify app at https://developer.spotify.com/dashboard, set the name and description to whatever you want, and set the redirect url to "http://localhost:8888/callback" (without the quotes). Then select Web API under "Which API/SDKs are you planning to use," agree to the TOS and design guidelines, then click save. Click on your app, then go to settings in the top right. Copy the client id into the variable at the bottom of the .py file called "client_id." Then show your client secret, make sure not to share with anyone, and then copy that and do the same thing, except pasting into the "client_secret" variable. Save your changes, and then I would make sure the program is in its own folder just to make it easy to find the .txt file, but it's up to you. Once you've done all of this, you can just run the script and it should generate a .txt file with every artist that's in your liked songs, excluding any local files you've added.
