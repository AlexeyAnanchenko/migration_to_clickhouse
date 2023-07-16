# migration_to_clickhouse
Задание на составление скрипта миграции витрины данных из Postgres в ClickHouse

Скрипт для миграции таблиц из PostgreSQL в Clickhouse находится по пути: (<code>[clickhouse_data/migrate.sql](https://github.com/AlexeyAnanchenko/migration_to_clickhouse/blob/main/clickhouse_data/migrate.sql)</code>)

Скрипты создания БД, загрузки данных и создания витрины расположены в папке postgres_data.

## Как развернуть проект?

Для просмотра проекта достаточно склонировать его себе на локальный компьютер, иметь установленным docker-compose и ввести команду:

```sh
docker-compose up -d
```

Далее базы данных доступны в контейнерах, либо по порту из любого сервиса для подключения к БД (например, DBeaver):
- PostgreSQL - порт 5432
- Clickhouse - порт 8123
