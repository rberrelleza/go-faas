FROM ramiro/openfaas-golang-base

ADD --chown=app:app https://raw.githubusercontent.com/openfaas-incubator/golang-http-template/master/template/golang-http/main.go /home/app/handler/
ADD --chown=app:app https://raw.githubusercontent.com/openfaas-incubator/golang-http-template/master/template/golang-http/go.mod /home/app/handler/

RUN go mod download