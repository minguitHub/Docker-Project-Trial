# Containerized Hello World Application

A simple Containerized Hello World Application built using Docker and Django. 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Docker

### Installing

Clone the main branch OR pull the image from Dockerhub (https://hub.docker.com/repository/docker/themagicalfishtaco/helloworld)

```
Git clone https://github.com/admu-zaavedra/project-submissions-group-name-pending.git

Docker pull themagicalfishtaco/helloworld:latest
```

(Optional)
* If pulling from github, build a docker image\
* If pulling from Dockerhub, skip

```
docker build -t <ImageName> .
```

Run container from docker image

```
docker run -d -p 8000:8000 <ImageName>
```

Basic Hello World website should appear at localhost:8000

```
localhost:8000
```

## Built With

* [Django](https://docs.djangoproject.com/en/3.2/) - The web framework used
* [Docker](https://docs.docker.com/) - Containerizing application used

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the latest(https://github.com/admu-zaavedra/project-submissions-group-name-pending/tags). 

## Authors
Arceo, Li Niko M.\
Beltran, Mark M.\
Co, Lance Michael O.\
Sumingit, Sylvane Q.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Application was containerized following https://dockerize.io/guides/python-django-guide
* Group was guided by Saavedra, Miguel Zenon Nicanor L.
