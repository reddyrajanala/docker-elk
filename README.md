# infrastructure

Docker container and compose scripts for core infrastructure services

## To start

```bash
  > cd into a folder in the repo.
  > docker-compose up -d
```

## Useful URLs:

### Kibana

Access Kibana at "http://<dockerhost>:5601"

The first time you run Kibana, it will need to be configured with an index-pattern. Set the index pattern as follows:

   Pattern: rompr-*
   Timestamp Field: @t


