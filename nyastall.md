##  Установка и запуск

### Важное примечание
Так как проект использует модульную систему JavaFX, точка входа в приложение находится в классе `Launcher.java`.

### Способ 1. Запуск через IntelliJ IDEA (для разработчиков)
1. Клонируйте репозиторий:
   ```bash
   git clone [https://github.com/ВАШ_НИКНЕЙМ/название-репозитория.git](https://github.com/ВАШ_НИКНЕЙМ/название-репозитория.git)
   Откройте проект как Maven Project.

Дождитесь загрузки зависимостей.

Перейдите в 
```bash
src/main/java/com/example/sorter/ и запустите файл Launcher.java (метод main).
```

### Способ 2. Запуск готового JAR-файла
Если вы собрали проект через Maven (mvn clean package), запустите его командой:

```bash
java -jar target/smart-file-sorter.jar
```
