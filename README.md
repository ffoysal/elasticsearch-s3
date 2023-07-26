# elasticsearch-s3
Setup Elasticsearch single node cluster with s3 compatible snapshot repository

It will create two single cluster with s3 backend pluin installed. Before running the please replace `<YOUR LOCAL HOST IP>` in the `docker-compose.yml` with your local IP address (not localhost, not 127.0.0.1)

After cloning the repo run `docker-compose up`


es01 instance running on http://localhost:9200 

es02 instance running on http://localhost:9201

minio instance running on http://localhost:9000 . use minioadmin/minioadmin for minio login

With this setup snapshot restore process can be easily tested.




