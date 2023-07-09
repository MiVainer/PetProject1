# PetProject1
nginx+lb+postgres+docker-compose+django

для связи Django с nginx использую gunicorn

создано 2 среды, тестовая (файл docker-compose.yml) и рабочая (docker-compose.prod.yml) доступная из вне на порту 1337 с любого ip-адреса (не ограничивал)
