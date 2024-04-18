# Installation

## Prerequisite

Helm, docker, kubernetes to be installed, up and running.

## If you need to modify this chart

Navigate to location where the oxalis folder is present and open it in your code editor like vscode.

If you dont want ingress to use then in values.yaml file set nginx-ingress.enabled=false and service.type=LoadBalancer

## Run Locally

Clone the project

```bash
  git clone https://github.com/InfoTechOps/devops
```

Go to the project directory

```bash
  cd helmcharts/
```

Package and install

```bash
  helm package oxalis/
  helm install oxalis-0.1.0.tgz
```

Access in your browser

```bash
  http://localhost
```

