FROM ramiro/openfaas-golang-base

ADD --chown=app:app https://raw.githubusercontent.com/openfaas-incubator/golang-http-template/master/template/golang-middleware/main.go /home/app/handler/
ADD --chown=app:app https://raw.githubusercontent.com/openfaas-incubator/golang-http-template/master/template/golang-middleware/go.mod /home/app/handler/

RUN go mod download