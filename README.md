#  Первый Jenkins проект в git

## Настройка
1. Создайте ssh ключ и добавьте в github
2. Добавьте закрытый ssh ключ в jenkins credentials
3. Создайте multibranch pipeline в jenkins
4. В секции `Branch Sources` выбрать `Git`, добавить SSH ссылку на репозиторий и выбрать ранее добавленный приватный ключ
5. В секции `Build Configuration` выбрать `By Jenkinsfile` и `Script Path` `Jenkinsfile`
4. Создайте Jenkinsfile с скриптом jenkins в корне проекта
5. Запустите jenkins repository scan