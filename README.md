# prometheus-operator-example

## Description
This project aims to be an example or skeleton for a prometheus deployment in kubernetes using the prometheus-operator and kustomize.

A more in detail description can be found in my [Blog](https://d4sw4r.github.io)

## Usage
1. Install custom CRD´s to your cluster. `kubectl create -k bootstrap/`
2. Install the prometheus-operator and example deployment.
`kubectl apply -k base/`
3. Enjoy!

## Motivation
Since I haven´t found any other blogs or guids about using prometheus-operator together with kustomize I did my own research and put this together as a good starting point for future usage.