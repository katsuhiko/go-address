# go-address

- https://www.codementor.io/codehakase/building-a-restful-api-with-golang-a6yivzqdo
- https://qiita.com/yasuno0327/items/be7fb992054f40b491cc

## Setup

```
cd go-address
docker run --rm -it -v ${PWD}:/go --workdir /go/src/api golang:1.12 go get -u github.com/golang/dep/cmd/dep
docker run --rm -it -v ${PWD}:/go --workdir /go/src/api golang:1.12 dep ensure
```

```
docker-compose up -d
```

```
http://localhost:8000/people
```


## Memo

### Initialize dep

```
docker run --rm -it -v ${PWD}:/go --workdir /go/src/api golang:1.12 dep init
```

