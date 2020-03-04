# ponysay
The 'ponysay' command is console application to display ponies speaking messagesl. 

The 'ponysay' command is a cowsay reimplemention with ponies.

## ponysay (Project Info)
[Website](https://erkin.party/ponysay/)

## Docker Hub
[Website](https://hub.docker.com/r/macabees/ponysay/)

## Build image
`$ docker build -t macabees/ponysay:latest .`

## Docker Push
`$ docker push -t macabees/ponysay:latest`

Note: requires `docker login`

## Run image
`$ docker run -it --rm macabees/ponysay 'Hello World!'`

## Help
`$ docker run -it --rm macabees/ponysay --help`
