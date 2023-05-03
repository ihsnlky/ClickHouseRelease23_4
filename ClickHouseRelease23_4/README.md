# ClickHouse Release 2023.3 New Features

## Prerequisites: 
You need to install "Docker Desktop" and "docker-compose" before tests.

## Steps
* Clone the repository to your local
```bash
git clone https://github.com/emoido/ClickHouseRelease23_3.git
```
* Go to the repository directory
```bash
cd ClickHouseRelease23_3
 ```
 * Run the following command for creating docker container
 ```bash
 docker-compose up -d
 ```
* After installation, you need to see the following nodes on your Docker Desktop Screen:
![Screenshot 2023-04-24 at 10 46 10](https://user-images.githubusercontent.com/45426637/233932019-76e78d5e-d729-4321-b93a-096403d8258d.png)

* **clickhouse01**, **clickhouse02** and **clickhouse03** are in the 23.3 version, and **clickhouse04** is in the 23.2 version.
* **clickhouse01**, **clickhouse02** and **clickhouse03** are configured as replication ready.

* You can use sample dataset(**uk_price_paid**) for tests.
The installation of this dataset is explained as follow:
https://clickhouse.com/docs/en/getting-started/example-datasets/uk-price-paid
