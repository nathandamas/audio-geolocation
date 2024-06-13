# Audio Geolocation

This project demonstrates a web-based application that allows users to geolocate a place by speaking its name. The application captures audio input from the user, transcribes the spoken location using Google Speech Recognition, and then uses the geopy library to geocode the location. Finally, it displays the location on an interactive map with Leaflet.js and provides voice feedback on the map's zoom level.

## Features

- **Audio Capture**: Capture audio input from the user via the browser.
- **Speech Recognition**: Transcribe the spoken location using Google Speech Recognition.
- **Geocoding**: Use the geopy library to geocode the transcribed location.
- **Interactive Map**: Display the location on an interactive map with Leaflet.js.
- **Voice Feedback**: Provide voice feedback on the map's zoom level.

## Requirements

To run this project, you will need the following libraries:

- Flask
- IPython
- geopy
- librosa
- soundfile
- speech_recognition
- pyaudio
- folium
- branca

You can install these libraries using pip:

```bash
pip install flask ipython geopy librosa soundfile speech_recognition pyaudio folium branca
sudo apt-get install ffmpeg portaudio19-dev
