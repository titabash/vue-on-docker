# vue-on-docker

## Install
1. Install docker, docker-compose

## How to build
1. Enter the project root<br>
   ```cd <project directory>```
2. Build docker<br>
   ```docker-compose up -d```
3. Enter the container<br>
   ```docker-compose exec web sh```
4. Build new vue app<br>
   ```vue create <project-name> -d```<br>
   Build Nuxs.js app<br>
   ```yarn create nuxt-app <project-name>```

## View logs
```docker logs <Container name> -f```

## Operation
- hoge<br>
  ```fuga```
