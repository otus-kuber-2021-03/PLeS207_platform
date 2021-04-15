# PLeS207_platform
PLeS207 Platform repository  
## Этапы выполнения ДЗ №1
1. Создал Dockerfile для nginx
2. Собрал и запушил образ в Docker Hub
3. Написал Манифест для запуска образа сделанного на предыдущем этапе
4. Добавил Init контейнер к манифесту
5. Добавил Volume
6. Проверил раболтоспособность всей системы
7. Восстановил работоспособность Hipster Shop и добавился статуса Running
## Этапы выполнения ДЗ №2
1. Запустил кластер kind на 3 мастер и 3 воркер ноды
2. Создал ReplicaSet для приложения frontend
3. Создал Deployment для приложения paymentservice
4. *Создал Deployment для приложения paymentservice в стратегии Blue-Green
5. *Создал Deployment для приложения paymentservice в стратегии Rolling Update
6. Добавил readinessProbe для приложения frontend
7. *Создал DaemonSet на примере node-exporter
8. ** Создал DaemonSet на примере node-exporter и для мастер нод
