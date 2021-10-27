React/Redux Streaming Application


![2021-10-27 15_45_40-React App](https://user-images.githubusercontent.com/8061492/139160211-c66c4e46-30e8-471e-95b7-7003e980c8ba.png)

The React app allows user to watch or create streams. Authentication is handled by the Google OAuth2 api. Once logged in, users can create and edit/delete streams that they own. Changes to the list of streams are made through RESTful API requests (using Axios) to the API server to modify the db.json file.

The video streams are handled by the RTMP server (node-media-server). Streaming is accomplished by configuring and running the client streaming software (OBS).

![2021-10-27 16_01_20-Modern React with Redux _ Udemy — Mozilla Firefox](https://user-images.githubusercontent.com/8061492/139160174-3d049c8c-2902-47fa-87fd-0ced47b37ce3.png)

Navigation: React-Router



This application was created as part of the Modern React with Redux course by Stephen Grider. 
