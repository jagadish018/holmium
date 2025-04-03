```
npm install
npm run dev
```

```
open http://localhost:3000
```

TO PUSH CHANGES TO THE REMOTE REPOSITORY:
Before we need to login 
az login
az acr login --name 1SI22IS400
```
docker build -t 1si22is400.azurecr.io/holmium:1.0.0 .
docker push 1si22is400.azurecr.io/dysprosium:1.0.0  
```
