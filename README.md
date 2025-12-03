[![Build Status](https://img.shields.io/endpoint?url=https%3A%2F%2Fstatusbadge-jx.apps.serv.run%2Fvillanova-k8s%2Fvillanova-k8s-database-service-controller)](https://github.com/villanova-k8s/devops-results/tree/logs/jenkins-x/logs/villanova-k8s/villanova-k8s-database-service-controller/master)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=villanova-k8s_villanova-k8s-database-service-controller&metric=alert_status)](https://sonarcloud.io/dashboard?id=villanova-k8s_villanova-k8s-database-service-controller)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=villanova-k8s_villanova-k8s-database-service-controller&metric=coverage)](https://villanova-k8s.github.io/devops-results/villanova-k8s-database-service-controller/master/jacoco/index.html)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=villanova-k8s_villanova-k8s-database-service-controller&metric=vulnerabilities)](https://villanova-k8s.github.io/devops-results/villanova-k8s-database-service-controller/master/dependency-check-report.html)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=villanova-k8s_villanova-k8s-database-service-controller&metric=code_smells)](https://sonarcloud.io/dashboard?id=villanova-k8s_villanova-k8s-database-service-controller)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=villanova-k8s_villanova-k8s-database-service-controller&metric=security_rating)](https://sonarcloud.io/dashboard?id=villanova-k8s_villanova-k8s-database-service-controller)
[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=villanova-k8s_villanova-k8s-database-service-controller&metric=sqale_index)](https://sonarcloud.io/dashboard?id=villanova-k8s_villanova-k8s-database-service-controller)


# Villanova Kubernetes Keycloak Controller

This project produces the Villanova Database Service Controller image. It is a run-to-completion style image
that processes a single VillanovaDatabaseService custom resource and deploys the specified database service as specified.

# How to build

```
mvn clean package -Pjvm
docker build . -f Dockerfile.jvm -t {image}
```

# Further info

For more information on how to configure this image, please consult the documentation in the [villanova-k8s-operator-common](https://github.com/villanova-k8s/villanova-k8s-operator-common) project
