# Covid19 Charts
Repository used to store and build charts

# Installation

## Prepare values.yaml file
Fill the needed value in you values.yaml

## Execution
```
helm repo add soa https://university-soa.github.io/covid19-chart/
helm repo update
helm install covid19-news soa/covid19-news -f values.yaml
```