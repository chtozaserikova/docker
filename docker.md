docker run -p 8888:8888 jupyter/scipy-notebook:6b49f3337709

docker exec -it af44749a7043  bash
docker cp marketing_campaign.csv af44749a7043:/home/jovyan/marketing_campaign.csv

docker run -v C:\Users\Sveta\projects\dockerstudying:/home/jovyan/ -p 8888:8888 jupyter/scipy-notebook:6b49f3337709

docker run -v C:\Users\Sveta\projects\dockerstudying:/home/jovyan/ -p 8888:8888 .
docker build -t my_notebook .

docker run -v C:\Users\Sveta\projects\dockerstudying:/home/jovyan/ -p 8888:8888 my_notebook  

docker-compose up

docker run --name some-postgres -e POSTGRES_PASSWORD=mysecretpassword -d -p 5432:5432 postgres