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
## Этапы выполнения ДЗ №3
1. Создана SA bob и добавлена роль admin
2. Создана SA dave
3. Создан NS prometheus
4. Создан SA carol
5. Настройка SA для NS prometheus на get, list, watch в отношении Pods
6. Создане NS dev
7. Создан SA jane, ken
8. Настройка роли admin для jane и роли view для ken
## Этапы выполнения ДЗ №4
1. Создание секрета для StatefulSet MinIO
2. Созданеие Stateful-Set
3. Создание Service для MinIO
