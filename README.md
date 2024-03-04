# Ocelot Gateway Proof of Concept (Poc)

## Introduction
This project is a proof of concept for an API gateway using Ocelot. It includes a simple API with two endpoints and demonstrates routing with Ocelot.

## Prerequisites
- .NET 5.0 or later
- Visual Studio 2019 or later (for development)

## Installation
Clone the repository to your local machine:

## Configuration
The `ocelot.json` file contains the routing configuration for the API gateway. It defines two routes:
- `/api/hello`: Routes to a HelloWorld endpoint on localhost port 7129.
- `/api/weather`: Routes to a WeatherForecast endpoint on localhost port 7129.

The API will be available at `https://localhost:<port>`, where `<port>` is the port number defined in the `launchSettings.json`.

## Endpoints
- `GET /api/hello`: Returns a simple "Hello World" message.
- `GET /api/weather`: Returns a weather forecast.

## Troubleshooting
- Ensure that the port number in the `ocelot.json` matches the port number where the SimpleApi is running.
- Check the application logs for detailed error messages.

## Contribution
Contributions are welcome. Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

Remember to replace placeholders (like <port> and the repository URL) with actual information. 
Also, this is just a basic template, and you may want to expand each section with more details specific to your project.
