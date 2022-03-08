# TMask_NIFI_Prometheus_Monitor
Monitoring przepływy NIFI za pomocą Prometheus i Grafana

=====================

Na początki NIFI Setting -> Reporting task

![NifiSetting](https://user-images.githubusercontent.com/75216446/157234965-f2d7270b-0b2d-41aa-b54b-ec33d1e6691a.png)


Dodajemy PrometheusReportingTaks

![PrometheusReportinTask](https://user-images.githubusercontent.com/75216446/157235028-01aec7a1-89cb-44be-8dae-f69f9a3e3558.png)

Do Grafana dodajemy source Prometheus i instalujemy odpowiedni [Dashboard](https://grafana.com/grafana/dashboards/12314)


Mamy bardzo wiele ciekawych informacji

JVM:


![dashboard1](https://user-images.githubusercontent.com/75216446/157235643-f69458a9-fe07-4e8e-9c2e-59fc3b795699.png)



Flowfiles:

![dashboard2](https://user-images.githubusercontent.com/75216446/157235766-d8fb4e06-dcad-4649-a58d-b646f27aaedf.png)
