If using any version of windows and the React app is not automaticall reloading after a code change.
Then add this environment vairable to the compose file:
services:
  environment:
    - CHOKIDAR_USEPOLLING=true