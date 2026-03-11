# Synergy Marine

Corporate website for Synergy Marine — a maritime/shipping company. Built with ASP.NET Core MVC (.NET 6).

## Pages

| Section | Description |
|---|---|
| Home | Landing page |
| About | Company profile, vision & mission, core values, HSE |
| Fleet | Fleet overview and specifications |
| Services | Capability spectrum and clients |
| News | Media coverage and press releases |
| Go Green | Sustainability initiatives |
| Licences & Certifications | Regulatory compliance documents |
| Careers | Job opportunities |
| Contact | Contact form |

## Tech Stack

- **Framework:** ASP.NET Core MVC
- **Language:** C#
- **Runtime:** .NET 6.0

## Getting Started

### Prerequisites

- [.NET 6 SDK](https://dotnet.microsoft.com/download/dotnet/6.0)

### Run locally

```bash
dotnet run --project synergymarine_v1
```

App will be available at `https://localhost:7232` or `http://localhost:5294`.

### Docker

```bash
docker-compose up
```

App will be available at `http://localhost:8080`.

## Build for Production

```bash
dotnet publish -c Release -o ./publish
```
