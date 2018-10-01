[![Travis](https://img.shields.io/travis/devabx/docker-python-nodejs.svg?style=flat-square)](https://travis-ci.org/nikolaik/docker-python-nodejs)
[![Pulls](https://img.shields.io/docker/pulls/devabx/python-nodejs.svg?style=flat-square)](https://hub.docker.com/r/nikolaik/python-nodejs/)
[![Release](https://img.shields.io/github/release/nikolaik/docker-python-nodejs.svg?style=flat-square)](https://github.com/nikolaik/docker-python-nodejs/releases)

## Python (latest) with Node.js 10.x based on [beevelop/nodejs-python](https://github.com/beevelop/docker-nodejs-python)
- Node: 8.x
- npm: 6.x
- yarn: stable
- Python: latest
- pip: latest
- pipenv: latest

----
### Pull from Docker Hub
```
docker pull nikolaik/python-nodejs:latest
```

### Build from GitHub
```
docker build -t devabx/python-nodejs github.com/devabx/docker-python-nodejs
```

### Run image
```
docker run -it devabx/python-nodejs bash
```

### Use as base image
```Dockerfile
FROM devabx/python-nodejs:latest
```

## Disclaimer
> This is experimental and might break from time to time. Use at your own risk!
