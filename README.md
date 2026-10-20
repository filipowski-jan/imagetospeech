# ImageToSpeech

ImageToSpeech is an ASP.NET Core Web API project (currently scaffolded with the default weather forecast endpoint) and serves as the backend foundation for the Image to Speech application.

## Tech Stack

- .NET 9
- ASP.NET Core Web API
- OpenAPI (Swagger document in development)

## Prerequisites

- [.NET 9 SDK](https://dotnet.microsoft.com/download)

## Getting Started

1. Clone the repository.
2. Navigate to the project root:

   ```bash
   cd /home/runner/work/imagetospeech/imagetospeech
   ```

3. Restore dependencies:

   ```bash
   dotnet restore
   ```

4. Run the API:

   ```bash
   dotnet run --project /home/runner/work/imagetospeech/imagetospeech/API/API.csproj
   ```

By default, the app runs on:

- `http://localhost:5109`
- `https://localhost:7099`

## API Endpoint

### GET `/weatherforecast`

Returns a sample 5-day weather forecast response in JSON.

Example request:

```bash
curl http://localhost:5109/weatherforecast
```

## Solution Structure

- `/API` – ASP.NET Core Web API project
- `imagetospeech.sln` – Solution file
