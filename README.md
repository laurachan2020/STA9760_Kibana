# STA9760 Project 3  Visualizing and Analysis on Kibana

## How to Run

Start:
docker-compose up -d

cd C:\project3\bigdata3

git pull

docker-compose down

docker images

docker rmi bigdata2_pyth -f

docker-compose up -d

docker-compose run pyth python tickets.py --page_size=10000 --num_pages=400

The above command will load violation parking data into Elasticsearch.

sh test_curl.sh > output.txt

Shutting off:
docker-compose down



