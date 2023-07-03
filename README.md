# ML_classifcation :Credit Default predictions-Banking Sector

Create first flask classifciation  machine learning project
```{link of repo}
[repo link](https://github.com/nomaan1112)
```
conda create -p venv python==3.7 -y
ml-classify

XGBoost model for credit card default prediction : ML projects
### Buld docker image
- Image name banking:latest
```
docker build -t <image name>:<tag name> .
```
python -m pip install --upgrade pip'

docker image flask_app and credit_card
docker image build -t <flask_docker> . # credit_card  //for docker <doker_banking>
docker run -p 5000:5000 -d <flask_docker> 
docker run --name flask1 -dit -p 5000:5000 a5f9c7a9a19f
docker run -p 5000:5000 -e PORT=5000 a5f9c7a9a19f

docker ps
docker stop <container_id>
docker login
##### renaming docker images
credit_card
docker tag flask_docker <your-docker-hub-username>/<flask-docker>

docker push <your-docker-hub-username>/<flask-docker>
docker images
docker login --username=<your-username> --password=<your-password>

To list docker image
```
docker images
```
Run docker image
```
docker run -p 5000:5000 -e PORT=5000 f3322f5e3b00
```
python -c 'import secrets; print(secrets.token_hex())'

To check runnig container in docker
```
docker ps
```

to stop docker container
```
docker stop <container_id> ad6cabc7a281
```
Creating yaml file
```
.github/workflows/main.yaml

### Buld docker image
```
docker build -t <image name>:<tag name> .
```
> Note: imagename fro docker must be lowercase

To list docker image
```
docker images
```
Run docker image
```
docker run -p 5000:5000 -e PORT=5000 <image name>
```

To check runnig container in docker
```
docker ps
```

to stop docker container
```
docker stop <container_id> 
```
Creating yaml file
```
.github/workflows/main.yaml
```
```
python setup.py install
```
install ipykernel
```
pip install ipykernel
```


### Final ramarks: ML Clssification projects
- docker images - banking
- get repo - MLops_classifcation
- heroku app - ml-classify
- local dir - MLops_classifcation
- Author - Keshav
- Sector - Banking
- Use case - Default of Credit Card clients of Bank
- Datasets - archive.ics.uci.edu/ml/datasets
- Final Data - kaggle - default-of-credit-card-clients-dataset
- labels 0 or 1 - 1 for default and 0 for not default
- Model - XGBClassifier
- Accuracy - 81 %
- Framework - Flask-Python
- environment - conda
