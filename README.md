### Домашнее задание к занятию 11 «Teamcity»
### Подготовка к выполнению
Виртуальные машины заущены и настроены
![image](https://github.com/EremeevAN/teamcity/blob/main/images/1.png)

### Выполнение ДЗ
Создадим форк проекта
![image](https://github.com/EremeevAN/teamcity/blob/main/images/2.png)

Проект в Team City
![image](https://github.com/EremeevAN/teamcity/blob/main/images/3.png)

Запуск сборки проекта. Результат:
![image](https://github.com/EremeevAN/teamcity/blob/main/images/4.png)
![image](https://github.com/EremeevAN/teamcity/blob/main/images/5.png)

build configuration в репозиторий
![image](https://github.com/EremeevAN/teamcity/blob/main/images/6.png)

отдельная ветка feature/add_reply в репозитории
![image](https://github.com/EremeevAN/teamcity/blob/main/images/7.png)

новый метод для класса Welcomer: метод должен возвращать произвольную реплику, содержащую слово hunter
![image](https://github.com/EremeevAN/teamcity/blob/main/images/8.png)

тест для нового метода на поиск слова hunter в новой реплике
![image](https://github.com/EremeevAN/teamcity/blob/main/images/9.png)

сборка самостоятельно запустилась, тесты прошли успешно.
![image](https://github.com/EremeevAN/teamcity/blob/main/images/10.png)

конфигурация так, чтобы она собирала .jar в артефакты сборки.
![image](https://github.com/EremeevAN/teamcity/blob/main/images/11.png)

повторная сборка мастера, убедитесь, что сборка прошла успешно и артефакты собраны.

В nexus загрузилась версия 0.0.3
![image](https://github.com/EremeevAN/teamcity/blob/main/images/12.png)

Артефакты jar
![image](https://github.com/EremeevAN/teamcity/blob/main/images/13.png)