## Ansible

Dockerfile & docker compose for running zookeeper 

Example run (Single container):

    docker run --name some-zookeeper -p 2181:2181 --restart always -d zookeeper
    
Example run (3 node cluster):
    
    docker-compose up