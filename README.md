# CUSTOM UI FOR KOVAAK 2.0
Live site: https://davidescalante.github.io/kovaakui/

I created a UI for personal performance tracking on specific scenarios. It supports six scenarios, which is enough for my focused use.

Unlike Kovaak's graphs, I have control over data display. The UI features
- a blue line for goal
- an orange line for current average performance
- and a red overlay for world average.

It provides a clearer view of my standing, overall performance, and score consistency compared to Kovaak's graph. 

It uses a this Google Sheets as database:
https://docs.google.com/spreadsheets/d/1j_JSnxNXp-

# OBS WIDGET
Using Node.JS is possible to feed and control the Kovaak site using the content inside the remote directory.

It needs:
- Node.JS
- socket.io

Once you have both installed, just can run server.js using `node server.js`. You should be able to access to both Kovaak widget and control panel from these URLs:
`http://localhost:3000/kovaakui/`
`http://localhost:3000/remote/`

To load it on OBS, load it as browser and use KovaakUI URL `http://localhost:3000/kovaakui/`

Once is loaded withing OBS, you should be able to externally control it using `http://localhost:3000/remote/`
