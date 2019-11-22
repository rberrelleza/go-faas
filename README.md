# Develop OpenFaaS functions with go and okteto

## Prerequisites
1. OpenFaas running in a K8S cluster.
1. faas-cli installed and configured.
1. okteto cli installed.


## Launch your functions
1. fass up -f stack.yml

## Develop your functions
1. Navigate to the function folder
1. `okteto up`
1. `okteto> fwatchdog`

The development environment is configured so that running `fwatchdog` picks up the latest changes using `go run` so you don't have to build anything. Just stop and relaunch `fwatchdog` to get the latest version.
