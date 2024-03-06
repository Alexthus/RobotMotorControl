# RobotMotorControl
# 1/ Общее описание проекта RobotMotorControl: цель проекта в получении управления двигателями робота с помощью функций motors_control и user_input.
# 2/ Описание работы с Git:
     a/ Создание и клонирование репозитория:
     
       - зарегистрировался на  Git Hub и создал новый репозиторий RobotMotorControl
       - зашёл в терминал и клонировал его на локальный компьютер с помощью SSH и команды:
         git clone git@github.com:Alexthus/RobotMotorControl.git 
         
     b/ Процесс сохранения изменений: Как предложил Git Hub, создал файлы и сделал коммит изменения:

       git init # инициализация git
       echo "# RobotMotorControl" >> README.md # создание файла
       git add README.md # добавление изменения
       echo "# Motor cotrol script in python here" >> motors_control.py # создание файла
       git add motors_control.py # добавление изменения
       git commit -m "first commit" # фиксация изменения
       git push # отправка изменения
       
      c/ Взаимодействие с ветками:
      
       git checkout -b feature_branch # создание новой ветки
       git branch #  просмотр имеющихся веток
       nano user_input.py # создание файла
       git add user_input.py # добавление изменения
       git commit -m "Added function for user input" # фиксация изменения
       git push --set-upstream origin feature_branch # отправка изменения  в новую ветку

      d/ Пул-реквесты:  как указано в задании зашёл на  Git Hub и выбрал  Compare&Pull request.
        Заполнил поля. Выбрал Create pull request.
        Затем закрыл запрос на pull.

      e/ Основные изменения и улучшения в коде: в этой ветке скажем будет отдельно тестироваться плавность переходных режимов работы моторов робота. Отдельная ветка создаётся, чтобы не нарушить уже отлаженный меанизм контроля.
      
    Заключение: Git понятный, дружелюный и удобный интрумент. 
