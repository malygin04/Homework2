# Домашняя работа по СПО № 2-3

# Автор
Малыгин Степан Викторович, студент группы Фт-320008

# Описание программы
Телеграм-бот, который умеет генерировать случайное число или спрашивать "как дела?".

# Последовательность для второго задания

1. Скачиваем docker desktop и регистрируемся в нём через github
2. Открываем wsl и копируем туда файлы с гита с помощью следующей команды: git clone https://github.com/mnxactep/spo-1-lab-shevtsov-ft-320007
3. Переходим в папку, куда был скопирован репозиторий: cd spo-1-lab-shevtsov-ft-320007
4. Создаём в этой папке файла без расширения под названием Dockerfile с помощью команды touch Dockerfile
5. Открывваем этот файл с помощью команды nano Dockerfile в режиме блокнота и заполняем следующим текстом:

# FROM python:3.9-slim
# WORKDIR /app
# COPY . /app
# CMD ["python", "main.py"]

6. Закрываем файл с помощью Cntrl + x , y, Enter
7. Вставляем в строку следующую команду: docker build -t telegram-bot:1.0 ./. 
8. Запускаем контейнер: docker run -it --name 
9. Приложение запустилось
10. Когда приложение завершило свою работу, останавливаем контейнер: docker stop lub_1_container
Готовый образ в разделе 'Images':

![image](https://github.com/user-attachments/assets/53041846-4530-48c5-990b-3469900ae986)
