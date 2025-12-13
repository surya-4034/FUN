Brief Description

This HTML page creates a custom YouTube multi-playlist dashboard using the YouTube IFrame API. It displays multiple YouTube playlists in a clean, responsive grid layout (up to 5 playlists per row) with a styled heading and YouTube play-button logo at the top. Each playlist loads in its own embedded player with a title above it. When one playlist starts playing, all other players automatically pause, ensuring only one audio source plays at a time. The page runs locally using a simple Python HTTP server and adapts smoothly to different screen sizes (desktop, tablet, and mobile).

To run :
    Step 1 :{on Terminal/CMD} run: python -m http.server 8000
    step 2:{on Browser} run: http://localhost:8000