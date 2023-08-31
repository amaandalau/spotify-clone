# HOW TO USE
### 1. Clone this repository

### 2. Look in the 'script.js' file
_The 2nd line is pretty important, let's look at the ***'client_id'*** variable first!_
- The `client_id` is your client ID. 
- To obtain your client ID: 
    - Go to [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/) and log in with your account.
    - Click on "Create an app".
    - Enter your app name and description, then click "Create".
    - You will be redirected to the app that you just created. <br/>
    ❗️❗️❗️IMPORTANT: Take note of your client ID.
    - Then, click on 'Edit Settings' and add the following redirect URIs one by one: <br/>
        http://127.0.0.1:5500 <br/>
        http://127.0.0.1:5500/
    - Once done, click 'Save'.
    <br/>
    
      _However, if your frontend is running at a different URL, you will need to add it to the redirect URIs._ <br/>
      _For example, if your frontend is located at http://127.0.0.1:3000, you will need to add the following redirect URIs:_ <br/>
      _http://127.0.0.1:3000_ <br/>
      _http://127.0.0.1:3000/_
        
### 3. Let's Try
Try opening it in a Live Server. You should be redirected to the Spotify authorization page. Then, <br/>
- Click "Agree". <br/>
_You will be redirected back after you authorized your application._
_You should be able to see the `access_token` in your browser's address bar._
_If you see the `access_token`, you are all set! Otherwise, make sure you have the correct `client_id`_

### 4. - End -
Have fun!
