# HNG DevOps Stage 1 - Personal API

A simple REST API built with Go, deployed on Ubuntu 22.04 with Nginx reverse proxy.

## Run Locally

```bash
go run main.go
```

## Endpoints

| Endpoint | Method | Response |
|----------|--------|----------|
| `/` | GET | `{"message": "API is running"}` |
| `/health` | GET | `{"message": "healthy"}` |
| `/me` | GET | `{"name": "...", "email": "...", "github": "..."}` |

## Live URL

https://akinbulejosamson.duckdns.org