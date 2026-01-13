# Документация к проекту

### Обновление пакетов

```
sudo apt-get update
```

### Установка Docker-Compose

```
apt-get install docker-engine
apt-get install docker-compose
```

### Клонирование репозитория

```
https://github.com/NikitaKolotushkin/lsfusion-wms.git

cd lsfusion-wms/
```

### Сборка и запуск

#### CRM

Запуск только CRM

```
cd Сrm/
docker-compose up -d
```

#### MyCompany

Запуск только MyCompany

```
cd MyCompany/
docker-compose up -d
```

**Ресурсы будут доступны в браузере по адресу: http://127.0.0.1:8080/**

## НО ВМЕСТЕ ОНИ НЕ МОГУТ СОСУЩЕСТВОАТЬ ПОКА ЧТО ТАМ НУЖНО ИЗМЕНИТЬ ПОРТЫ И ИЗМЕНИТЬ КОНФИГИ В СЕРВЕРЕ И КЛИЕНТЕ
