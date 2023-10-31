# pdns-docker
This repository uses for powerdns auth, recursor, admin portal for my home-lab.  

```
export PDNS_AUTH_API_KEY=YOUR_KEY
export PDNS_WEBSERVER_PASSWORD=YOUR_PASSWORD
```
  
## AUTH with PowerDNS Admin
```
docker compose -f docker-compose.auth.yml up -d
```

## AUTH with PowerDNS Admin and proyx
```
docker compose up -d
```
