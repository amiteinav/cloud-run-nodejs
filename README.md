# cloud-run-nodejs
Steps for setting up a Cloud Run of a Node.js

After cloning the repo

```
cd cloud-run-nodejs
npm install
```

Local testing
```
node app.js
```
Navigate your browser to http://your_server_ip:8080. You will see the landing page

Build the docker
```
docker build . -t gcr.io/PROJECT_NAME/cloud-run-nodejs
```

Run the docker
```
docker push gcr.io/PROJECT_NAME/cloud-run-nodejs
```
