# Bookinfo Rating Details

Book Details service has been developed on Ruby



## How to run with Docker

```bash
# Build Docker Image for rating service
docker build -t details .

# Run ratings service on port 8080
docker run -d --name details -p 8081:8081 details
```

* Test with path `/ratings/1` and `/health`
