# go-hello-chi

Part of a comparision of [Go HTTP routers](https://github.com/avelino/awesome-go/blob/master/README.md#routers).

1. https://github.com/go-chi/chi


## Usage

### Invocation

```console
go-hello-chi
```

In a web browser, visit http://localhost:3000/

## Development

### Dependencies

#### Set environment variables

```console
export GOPATH="${HOME}/go"
export PATH="${PATH}:${GOPATH}/bin:/usr/local/go/bin"
export PROJECT_DIR=${GOPATH}/src/github.com/docktermj
```

#### Download project

```console
mkdir -p ${PROJECT_DIR}
cd ${PROJECT_DIR}
git clone git@github.com:docktermj/go-hello-chi.git
```

#### Download dependencies

```console
cd ${PROJECT_DIR}/go-hello-chi
make dependencies
```

### Build

#### Local build

```console
cd ${PROJECT_DIR}/go-hello-chi
make
```

The results will be in the `${GOPATH}/bin` directory.


