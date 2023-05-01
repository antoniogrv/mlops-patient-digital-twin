[![Deploy to Amazon ECS](https://github.com/antoniogrv/mlops-patient-digital-twin/actions/workflows/__DEPLOY-ECR-ECS.yml/badge.svg)](https://github.com/antoniogrv/mlops-patient-digital-twin/actions/workflows/__DEPLOY-ECR-ECS.yml)

## Esecuzione

```
docker build --tag mlops-pdt .
docker run --publish 80:80 mlops-pdt
```

## Architettura

![Architettura](https://github.com/antoniogrv/patient-digital-twin/blob/master/docs/cloud_arch.png)
