# GitHub Actions Exercise

An exercise for 'DevOps and SRE' on HTW Berlin
![Fancy](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.brafton.com%2Fwp-content%2Fuploads%2F2013%2F07%2Ffancy-dark-logotype.png&f=1&nofb=1)


## Test

```bash
go test ./...
```

## Build

```bash
docker build . -t my-app
```

## Run

```bash
docker run -p 8080:8080 my-app
```
