# Weniverse-1st-online-prototype
WENIVERSE is an immersive get-together space for people to connect.

This 1st iteration is really a novice experimenting with coding in the 3D space. 
# <a href="https://weniverse.herokuapp.com/">A live version of weniverse is avaiblable here</a>
https://weniverse.herokuapp.com/


This is a very basic video and chat in a 3D. 

To run locally:
In the project folder, use terminal to install node server:
<code>  npm install </code>
Then run it:<code>  node server.js </code>

To run online, you can use heroku https://dashboard.heroku.com/
To use this code online, you'll need to add your ICE credentials to the server.js file. Look for this code and replace it with credentials. 

<code>
// insecure method for testing:<br/>
const accountSid = "ENTER YOURS from https://www.twilio.com/"; <br/>
const authToken = "ENTER YOURS from https://www.twilio.com/";<br/>
</code>

you can recieve them from twillio by creating a project and extending its info - https://www.twilio.com/

This was developed with instruction and source code from Aidan Nelson
https://github.com/AidanNelson/YORB2020
Who borrowed code from:
https://github.com/juniorxsound/THREE.Multiplayer
https://github.com/Miczeq22/simple-chat-app
https://github.com/zacharystenger/three-js-video-chat
