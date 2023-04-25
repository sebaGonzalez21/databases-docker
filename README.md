# databases-docker

databases in docker for use

## Usage

1. Define dbms setup values in:

```
.env
```

2. Start the service, next example runs an sqlserver instance:

```
docker-compose up sqlserver
```

3. Post setup(SHOULDN'T be any)
```
   (sudo) pg_createcluster 11 postgres11_cluster01
   
   postgres11_cluster01 start
```