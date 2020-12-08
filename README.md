# covid19 News - Helm Chart

This helm chart combines the microservices need for covid19 news application to run. It deploys:
- [covid19-vuejs-frontend](https://github.com/university-soa/covid19-vuejs-frontend)
- [covid19-news](https://github.com/university-soa/covid19-news)

## How to deploy
```
git clone https://github.com/university-soa/covid19-chart
cd covid19-chart
helm install <release-name> .
```