# Kittygram

Kittygram - социальная сеть, созданная специально для любителей котиков, которые хотят делиться увлекательными фотографиями своих пушистых компаньонов. Этот проект включает в себя полностью функциональное бэкэнд-приложение на Django и фронтэнд-приложение на React.

## Возможности проекта

- Регистрация и авторизация пользователей
- Добавление и изменение профилей котиков
- Просмотр и взаимодействие с публикациями других пользователей

## Подключение к Kittygram

Для доступа к проекту Kittygram, вам потребуется следующее:

- Клонировать репозиторий

```
git clone git@github.com:YaStirayuLaskoy/infra_sprint1.git
```

- Установить зависимости для бэкэнд-приложения Django

```
python3 -m venv venv
```

```
source/bin/activate/
```

```
pip install -r requirements.txt
```

```
python3 manage.py migrate
```

- Установить зависимости для фронтэнд-приложения React

```
npm i
```

```
npm run build
```

- Перезапустите приколы

```
sudo systemctl daemon-reload
```

```
sudo systemctl reload nginx
```

- Настроить файл .env в дериктории с setiings.py с необходимыми секретами. (смотреть env.template)

## Безопасность проекта Kittygram

Для обеспечения безопасности проекта Kittygram, секреты подгружаются из файла .env. В файле .env содержатся важные константы, такие как SECRET_KEY, которые строго исключены из хранения в коде проекта.

## Стили для панели администратора

В проекте Kittygram предусмотрены стильные таблицы стилей для панели администратора, чтобы улучшить визуальное впечатление и опыт пользователей.


