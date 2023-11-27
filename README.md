# Nginx Proxy to HAProxy stats

In a deployment we have NGinx acting as a reverse proxy to wards the HAProxy stats page. This is a simple configuration to do so,

# using the stack

To use the stack, run:

```
docker compose up -d
```

if everything goes well, you should be able to access the main  page at http://localhost:8080 - the user and pass will be requested the first time you connect to the seperate sites.

