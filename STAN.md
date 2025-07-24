# How to build for Play.Stan

## Build

- python3 build/build.py --name play +@complete -@cast -@cea -@devices -@mss -@offline -@polyfillForUI -@ui --force
- python3 build/build.py --name play-hls +@complete -@cast -@cea -@devices -@mss -@offline -@polyfillForUI -@ui -@dash --force
- python3 build/build.py --name play-dash +@complete -@cast -@cea -@devices -@mss -@offline -@polyfillForUI -@ui -@hls -@fairplay --force
