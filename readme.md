# Weather App

In this project you can know or consult the weather around the world, check out your country and know if the comvinient the weather for you.
The weather application in this case uses 3 main concepts, select a country though a global map, reflect the general weather in that country showing its climatic data , and showing the country's flag.

## The application

You can check the application here: [Live Code App](https://rvjonh-weatherapp.netlify.app)

Note: to render the globe map uses Canvas with three.js technology with requires a computer with medium characteristics of processing. so in some machines can work slowly.

## Features

* Go through a globe map aroung the world selecting different countries and knowing many points of them, like his name, population, PIB.
* Check their current weather with its weather code and know if its a (clear, rain, thumder, snow) day.
* Check the actual date, general temperature, the day and the humidity of the country.
* See the country's flag you prefer.
* Refresh how many times you want you desire.

## Tech stack

* Html
* Css (Sass)
* Javascript (React)
* Three.js

### Third part software

It's required to mention some open sourse project that allow me to build this project, and these are:

This allows draw a globe of the world:

* react-globe.gl : React component for Globe Data Visualization using ThreeJS/WebGL
    [Repository](https://github.com/vasturiano/react-globe.gl)

This allows to draw the lines polygons in the map for the countries:

* geojson.xyz : A simple, open source website, CDN, and CLI utility for the fast access of GeoJSON data for web mapping examples and experiments.
    [Website](http://geojson.xyz/)

This allows to request climatic data from a server base of latitude and longitude:

* Free Weather API : Open-Meteo is an open-source weather API with free access for non-commercial use. No API key is required. You can use it immediately!
    [Website](https://open-meteo.com/)

This allow to show the country's flag:

* Country Flags API : Get a country's flag via the country's name, UN Code, ISO Alpha-2 code, or ISO Alpha-3 code. These codes can all be found at iban.com. This API was designed to save developers time from having to download hundreds of flags and handling different cases for identifying how to get a certain country's flag (by name or by code). The flags are also free to use in the public domain.
    [Website](https://www.countryflagsapi.com/)


## Development

Requirements:

* Git - version control system for software
* Node.js
* A text editor

In a Terminal or a CLI, be in your prefer folder and ..

Clone the repository

```bash
    git clone https://github.com/Rvjonh/WeatherApp.git
```

Enter the directory and install dependencies

```bash
    cd WeatherApp && npm i
```

Execute the development server

```bash
    npm run dev
```

### For deployment

```bash
    npm run build
```

Further information, consult [ViteJs](https://vitejs.dev/)
