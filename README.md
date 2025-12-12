# microservices-platform
Микросервисная инфраструктура Kubernetes, Java app, Postgres, Kafka, Redis и мониторинг (Grafana + Prometheus)

## Как запустить проект: 
1. Открыть Docker Desktop и включить в натсройках **Enable Kubernetes**. ( Docker Desktop https://docker.com/products/docker-desktop )
2. Скачать zip-архив репозитория microservices-platform или с помощью git.
   ```git clone https://github.com/porfolie-Chizhov-Vitaliy/microservices-platform.git ``` 
3. Запустить файл deploy_for_Windows/Linux и дождаться выполнения.
  
## Как проверить работоспособность и отображение информации в Grafana:
1. Зайти в Grafana (login:admin password:admin)
2. Запустить скрипт для генерации 100 платежей scripts/for_windows|linux/100_add_payments.bat
3. Проверить информацию на дашбордах  
   

### Схема кластера:
**pod** - название пода

**image** - образ который используется в deployment

**port** -  порт внутри кластера 

**targetPort** - порт внутри пода (порт контейнера)

**nodePort** - порт доступ извне кластера

![kuber cluster v2](https://github.com/user-attachments/assets/3cc0e27e-0332-4eba-9b36-82e6beebde26)






  
