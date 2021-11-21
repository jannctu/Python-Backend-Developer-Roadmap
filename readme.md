# Python Backend Developer Roadmap 

This roadmap is intended for junior software engineers in my company or newcomers in my team for onboarding purposes. Generally, this is for Python Backend Web Developer with a speciality in Instant Messager using [Matrix](matrix.org). 

## 1. Basic Internet, Operating System and Frontend Knowledge
###	1.1 Bash/Terminal
- SSH
- ["Mastering Linux shell scripting a practical guide to Linux command- line, Bash scripting, and Shell programming"](https://www.goodreads.com/book/show/40615121-mastering-linux-shell-scripting)

### 1.2 Basic Internet
- DNS 
- Domain
- Hosting 
- Cloud service 
- resources
	- [DNS & Domain](https://pediaa.com/difference-between-domain-and-dns/)
	- [Cloud & Hosting](https://cloudacademy.com/blog/web-hosting-vs-cloud-hosting-whats-the-difference/)

### 1.3 Web server 
- Nginx, Apache, Tomcat
- Reverse Proxy
- Load balancer 
- WSGI & ASGI
- Resources
	- [Nginx](https://www.nginx.com/resources/glossary/nginx/)
	- [Reverse Proxy](https://docs.nginx.com/nginx/admin-guide/web-server/reverse-proxy/)
	- [Load Balancer](https://docs.nginx.com/nginx/admin-guide/load-balancer/http-load-balancer/)
	- [WSGI & ASGI](https://medium.com/analytics-vidhya/difference-between-wsgi-and-asgi-807158ed1d4c)

## 2. Programming language (Python)
### 2.1 Basic Data Structure & Algorithm
- Resources
	- [Python Basic](https://books.goalkicker.com/PythonBook/)
	- [Data Structure with Python](https://www.geeksforgeeks.org/data-structures/)

### 2.2 Python2 vs Python3
- Resource 
	- [Python2 vs python3](https://www.guru99.com/python-2-vs-python-3.html)

### 2.3 OOP 
- class
- Inheritance
- etc..
- resources
	- [Python 3 Object Oriented Programming](https://www.goodreads.com/book/show/8679996-python-3-object-oriented-programming)

### 2.4 Python data type 
- list
- queue
- stack
- tree
- dictionary 
- tuple 
- hash map
- set

- Resources
	- [Python Basic](https://books.goalkicker.com/PythonBook/)

### 2.5 Environment & environment manager 
- pip
- env & venv
- [conda](https://docs.anaconda.com/anaconda/user-guide/getting-started/)
- resources
	- [python environment manager](https://www.section.io/engineering-education/introduction-to-virtual-environments-and-dependency-managers/)
	- [env](https://docs.python.org/3/tutorial/venv.html)
	- [conda cheat sheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf)

### 2.6 Python IDE 
- Visual studio Code
- Pycharm
- Sublime
- Text Editor

### 2.7 SOLID Principe
- [Solid principe with python](https://towardsdatascience.com/solid-coding-in-python-1281392a6a94)

### 2.8 Python Framework (web)
- [FastAPI](https://fastapi.tiangolo.com/) 
- [Flask ](https://flask.palletsprojects.com/en/2.0.x/tutorial/index.html)
- [Django](https://www.djangoproject.com/)

### 2.9 Unit Testing 
- [pytest](https://docs.pytest.org/en/6.2.x/)
- Unittest

### 2.10 Important Library 
- numpy 
- requests
- socket.io
- psycopg2
- bcrypt
- aioredis
- stomp.py
- json
- asyncio
- time
- logging
- typing 
- sqlalchemy
- gunicorn
- urllib
- matrix_client
- matrix-nio
- pyyaml
- pandas
- pytest

### 2.11 Python ASGI 
- [gunicorn](https://docs.gunicorn.org/en/stable/)
- [uvicorn](https://www.uvicorn.org/settings/)

### 2.12 Data Model 
- ORM (Object Relational Mapping)
	- [SQLAlchemy](https://docs.sqlalchemy.org/en/14/)
- Resources
	- [ORM](https://www.fullstackpython.com/object-relational-mappers-orms.html)

### 2.9 Advanced Concept 
- Decorator / Property (@) [tutorial](https://www.programiz.com/python-programming/decorator) [tutorial2](https://www.datacamp.com/community/tutorials/decorators-python)
- Synchronous & Asynchronous [Asyncio Python](https://docs.python.org/3/library/asyncio.html)
- Multithreading [python Multithreading](https://www.tutorialspoint.com/python/python_multithreading.htm)
- python modules [modules & package](https://realpython.com/python-modules-packages/)

## 3. Version Control 
### 3.1 Git/Github
- resources
	- [Git documentation](https://git-scm.com/docs)
	- "Pragmatic version control using Git"

## 4. Database
### 4.1 Posgresql 
- Resource 
	- [Postgresql tutorial](https://www.postgresqltutorial.com/)

### 4.2 [Databse Index](https://www.postgresql.org/docs/9.1/indexes.html) 
### 4.3 SQL (Query Language) [tutorial](https://www.tutorialspoint.com/sql/index.htm)
### 4.4 [Normalization](https://www.guru99.com/database-normalization.html)
### 4.5 [ACID](https://henriquesd.medium.com/acid-properties-43e146b21e0d) 
### 4.6 [ORM](https://medium.com/@haataa/orm-for-python-sqlalchemy-101-with-code-example-60868e65b0c)
### 4.7 [NoSQL](https://towardsdatascience.com/datastore-choices-sql-vs-nosql-database-ebec24d56106)  
- MongoDB
- Elastic Search 
- InfluxDB 
- DynamoDB

## 5. [APIs](https://medium.com/@perrysetgo/what-exactly-is-an-api-69f36968a41f)
### 5.1 [Rest API](https://medium.com/edureka/what-is-rest-api-d26ea9000ee6) 
### 5.2 [Json](https://restfulapi.net/introduction-to-json/)
### 5.3 [GraphQL](https://graphql.org/)

## 6. [Caching](https://aws.amazon.com/caching/)
### 6.1 In Memory caching
- Redis [tutorial](https://aws.amazon.com/redis/) [Redis python](https://realpython.com/python-redis/)
- [memcached](https://memcached.org/)

### 6.2 Content caching
- [CDN](https://www.cloudflare.com/learning/cdn/what-is-a-cdn/)

## 7. Testing
### 7.1 [Unit testing](https://www.guru99.com/unit-testing-guide.html) 
### 7.2 Tools 
- pytest
- unittest
- [Postman](https://www.postman.com/)

## 8. [CI / CD](https://medium.com/devops-dudes/what-is-ci-cd-continuous-integration-continuous-delivery-in-2020-988765f5d116) 
### 8.1 Version Control 
### 8.2 Github/Gitlab 
### 8.3 CI/CD tools 
- [github action ](https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions)
- [jenkins](https://www.jenkins.io/)
- [travis](https://travis-ci.org/)

## 9. Architectural Patterns
### 9.1 [Monolithic](https://microservices.io/patterns/monolithic.html)
### 9.2 [Microservice](https://microservices.io/)
### 9.3 Patterns
- [SAGA](https://microservices.io/patterns/data/saga.html)
- [Circuit breaker](https://microservices.io/patterns/reliability/circuit-breaker.html) 

### 9.4 Design Pattern 
- Singleton 
- Strategy 
- Command 
- Observer

- Resources 
	- [Design Pattern]https://refactoring.guru/design-patterns

## 10. [Message Broker](https://www.ibm.com/cloud/learn/message-brokers)
### 10.1 Communication concept 
- Producer & consumer
- publisher & subscriber 
- topic 
- queue

### 10.2 Engine 
- [ActiveMQ](https://activemq.apache.org/)
- [RabbitMQ](https://www.rabbitmq.com/)
- [Kafka](https://kafka.apache.org/)

## 11. Containerization
### 11.1 [Docker](https://docs.docker.com/) 
### 11.2 [Kubernetes](https://kubernetes.io/docs/home/)
## 12. Authentication
### 12.1 [JWT](https://auth0.com/blog/how-to-handle-jwt-in-python/)
### 12.2 [OAuth2](https://testdriven.io/blog/oauth-python/)
### 12.3 hash function 
- sha
- [bcrypt](https://zetcode.com/python/bcrypt/)

## 13. Communication Protocol 
### 13.1 [Websocket](https://www.html5rocks.com/en/tutorials/websockets/basics/)
### 13.2 TCP
### 13.3 [STOMP](https://jasonrbriggs.github.io/stomp.py/)
### 13.4 WEbRTC
### 13.5 Http Request
### 13.6 [gRPC](https://grpc.io/docs/languages/python/basics/)

## 14. [Monitoring](https://www.pcwdld.com/best-python-monitoring-tools)
### 14.1 Engine 
- [Grafana](https://grafana.com/)
- [Datadog](https://www.datadoghq.com/)
- [Prometheus](https://prometheus.io/)
- Sentry