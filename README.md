# ASP.NET .NET CORE 5.0 API

## Dependencies
- [.NET Core 5.0](https://dotnet.microsoft.com/download/dotnet/5.0)
- [Docker](https://docs.docker.com/get-docker/)

## Installation


Clone this repo
```
git clone https://github.com/marvincorreia-dg/WeatherForecast
cd WeatherForecast
```
### Local
Install dependencies and run app
```
dotnet restore
dotnet run
```

### Docker
Build app docker image
```
docker build -t weather . 
```

Run app container
```
docker run -dp 7000:80 weather
```