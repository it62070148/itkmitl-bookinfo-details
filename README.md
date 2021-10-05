# How to run details service

## Prerequisite

* Ruby 2.7

```bash
ruby details.rb 9080
```

## How to run with Docker

```bash
# Build Docker Image for productpage service
docker build -t details .

# Run productpage service on port 8081
docker run -d --name details -p 8081:9080 details
```

* Test with path `/details/1` and `/health`
