# Metronome for LIFX 
Pulses LIFX lights to the beat of songs being currently played on Spotify

# Set Up
1. Get LIFX token

![alt text](https://discourse-cdn-sjc2.com/standard17/uploads/lifx/optimized/1X/f27580c296f07b32152239c037bf9c964f05444a_1_690x394.gif)

2. Get Spotify client id and client secret
- Visit https://developer.spotify.com/dashboard/

- Create an app 

![alt text](https://github.com/codycoogan/metronomeforlifx/blob/master/images/spotclient.gif)

- Here are your credentials
![alt text](https://github.com/codycoogan/metronomeforlifx/blob/master/images/spotblurred_g.jpg)

- In the Spotify project settings add https://www.google.ca/ as the redirect URI (PIC?)


3. Fill out metronomeconfig.txt
- Open metronomeconfig.txt
- Paste your LIFX token and your Spotify client id and secret in the respective spots in the file
- Save the file

4. Install requirements.txt
- After downloading requirements.txt open terminal or command prompt
- Go to the directory where this project is saved in
- Run pip install -r requirements.txt in the command line

5. How to sign in to Spotify in app
- Run program 
- Sign in to Spotify account when prompted in browser
- If sign in was successfull, copy the URL of the page that you were redirected to after signing in (google.ca)
- Paste this URL into prompt in command line


TEST NEW RANDOM AND SUBMIT NEW FILEG

# How To Use
