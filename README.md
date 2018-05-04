# FoundationDB


Docker image for running [https://www.foundationdb.org](https://www.foundationdb.org)

## Run:

* docker run -p 4500:4500 chr1st0ph/foundationdb-docker

## How to connect using fdbcli:

* docker ps -a ( for getting CONTAINER_ID )
* docker exec -it CONTAINER_ID fdbcli