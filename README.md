# Audio Geolocation

 ![Badge em Desenvolvimento](https://img.shields.io/badge/license-MIT-blue) 
 
 ![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)

Este código foi desenvolvido como projeto final para a disciplina de CGEO7046 – Tópicos Especiais III Processamento de Linguagem Natural em Ciências Geodésicas - 
Inteligência Artificial Geoespacial (IAG) e Processamento de Linguagem Natural (PLN) - do Programa de Pós Graduação em Ciências Geodésicas (PPGCG) da Universidade Federal do Paraná (UFPR), no ano de 2024. 
-------------------------------------------------------------------------------------------------------------------------------------------------------------------

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#requirements">Requirements</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#running-the-application">Running the application</a></li>
    <li><a href="#notes">Notes</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

## About The Project

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




You can install these libraries using pip. 
```
pip install flask ipython geopy librosa soundfile speech_recognition pyaudio folium branca
```
Additionally, you will need to install the ffmpeg and portaudio packages:
```
sudo apt-get install ffmpeg portaudio19-dev
```
## Usage

    1. Start the Flask Server
    2. Audio Processing and Geolocation

## Running the Application

    Open the project in Google Colab.
    Execute the cells in the given order:
        The cell starting the Flask server.
        The cell handling the audio recording and geolocation.
    Follow the instructions to speak the location you want to geolocate.
    View the resulting map with the specified location marked and listen for the voice feedback on the zoom level.

## Notes

Ensure you have an active internet connection for Google Speech Recognition and geocoding services.
This project is intended to run in a Google Colab environment.

## License

This project is licensed under the MIT License.
