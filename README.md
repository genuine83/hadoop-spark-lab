# Небольшой кластер Hadoop для Spark разработки, собранный на Docker-compose

### Собираем образ

```bash
docker build . -t hadoop-spark-baseline
```

### Стартуем кластер

```bash
docker-compose up -d
```

### Адрес YARN UI

http://localhost:8088/cluster/nodes

### Выключаем все по завершении

```
docker-compose down
```