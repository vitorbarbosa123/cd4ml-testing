# Continuous Delivery for Machine Learning

## Todo
## Tools used 

* [Python 3.9](https://www.python.org/downloads/release/python-399/)
* [Docker](https://www.docker.com/)
* [Jenkins](https://jenkins.io/)
* EFK Stack, [ElasticSearch](https://www.elastic.co/elasticsearch/), [Fluentd](https://www.fluentd.org/), [Kibana](https://www.elastic.co/kibana) 
* [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/)
* [MLFlow](https://mlflow.org)
* [Minio](https://min.io/)

## Running

- Create jenkins/jenkins-admin-password.txt before run docker-compose

```
docker-compose up -d --build --remove-orphans
```
## Links to the different components of this scenario

home [here](http://localhost:3000)

* [Jenkins](http://localhost:10000/blue)
* [JupyterLab](http://127.0.0.1:8888/lab)
* [MLFlow](http://localhost:12000)
* [The ML Model](http://localhost:11000)
* [Kibana/fluentD/Elasticsearch](http://localhost:5601/app/kibana)
* [Minio](http://localhost:9000)