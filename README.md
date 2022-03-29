# SCA-Cloud-School-Application


## Steps
Deploy a  simple Flask app, confirm it run using the script below
``` 
    set FLASK_APP=app.py
    run flask
```

### Dockerise the application
> Build the Docker image
> Run the docker image using
```
    sudo docker build --tag sca-docker-app .
    sudo docker run --name sca-docker-app -p 5000:5000 sca-docker-app
```

![Build and run App](sca.png)

### Other Steps
View Application on Broswer using http://127.0.0.1:5000
make changes to app file and pushed to branch - Feature

### Docker hub
Rebuild docker Image  and 
pushed to dockerhub-- https://hub.docker.com/r/chisomjude/sca-app
```
    docker tag sca-app chisomjude/sca-app
    docker push chisomjude/sca-app
```