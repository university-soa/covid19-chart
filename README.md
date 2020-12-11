# covid19 News - Helm Chart

This helm chart combines the microservices need for covid19 news application to run. It deploys:
- [covid19-vuejs-frontend](https://github.com/university-soa/covid19-vuejs-frontend)
- [covid19-news](https://github.com/university-soa/covid19-news)
- [covid19-external-golang](https://github.com/university-soa/covid19-external-golang)
- [covid19-asp-net-core](https://github.com/university-soa/covid19-asp-net-core)

## How to deploy
```
git clone https://github.com/university-soa/covid19-chart
cd covid19-chart
helm install <release-name> .
```

## How to update
```
helm update <release-name> .
```