# ClickHouse Release 23.4 New Features

## Prerequisites: 
You need to install "Docker Desktop" and "docker-compose" before tests.

## Steps
* Clone the repository to your local
```bash
git clone https://github.com/ihsnlky/ClickHouseRelease23_4.git
```
* Go to the repository directory
```bash
cd ClickHouseRelease23_4
 ```
 * Run the following command for creating docker container
 ```bash
 docker-compose up -d
 ```
* After installation, you need to see the following nodes on your Docker Desktop Screen:
<img width="1050" alt="Screenshot 2023-05-03 at 19 58 48" src="https://user-images.githubusercontent.com/110613255/235987231-255b0e76-ad8d-4b3c-b74b-6315af8f540e.png">


* **clickhouse01**, **clickhouse02** and **clickhouse03** are in the 23.4 version, and **clickhouse04** is in the 23.3 version.
* **clickhouse01**, **clickhouse02** and **clickhouse03** are configured as replication ready.

* You can use sample dataset(**uk_price_paid**) for tests.
The installation of this dataset is explained as follow:
https://clickhouse.com/docs/en/getting-started/example-datasets/uk-price-paid
