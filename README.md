# djstripe

Чтобы запустить программу делаем следующие шаги:
1) Клонируем репозитрий (git clone <Https ссылка>)
2) Открываем проект с помощью IDE
3) Создаем виртуальное окружение(python -m venv <имя_окружения>)
4) Входим в виртульное окружение (в комндной строке заходим сначала в папку проекта и пишем venv\Scripts\activate это для операционной системы windows)
5) Делаем миграции(сначала в командной строке набираем команду python manage.py makemigrations, потом python manage.py migrate)
6) Создаем суперюзера (python manage.py createsuperuser)
7) Запускаем приложение (python manage.py runserver)
8) Открываем браузер и в адресной строке вводим http://127.0.0.1:8000/admin
9) Заходим в админ панель только что созданной суперюзером
10) В разделе PRODUCTS нажимаем на кнопку +Add
11) В строке Name пишем название продукта, в строке Price пишем цену товара. Потом нажимаем на кнопку SAVE
12) В адресной строке браузера пишем http://127.0.0.1:8000 и видим наш продукт и можем его покупать