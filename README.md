# Server-sent events for ELM

This repo contains the original sample project that integrates SSE (server-sent events) in Elm 0.18. The implementation is 
using a rails 6 as backend demo.

elm.js is already build inside the rails public/js directory

This is only provided as a working demo, straigtforward from the original (as on Feb 2019), so no port to 0.19 has been made.
Steps:

1- from src/server , do the bundle install

2- rails s -p 8080

3- open localhost:8080 inside your favorite browser (FF, Safari or Chrome required)
