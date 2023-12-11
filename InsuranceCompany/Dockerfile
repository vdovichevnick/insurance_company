# Используйте официальный образ OpenJDK для Java 17
FROM openjdk:17-oracle

# Установите рабочую директорию внутри контейнера
WORKDIR /app

# Копируйте JAR-файл вашего Spring приложения в контейнер
COPY target/security-0.0.1-SNAPSHOT.jar app.jar

# Запустите Spring приложение при запуске контейнера
CMD ["java", "-jar", "app.jar"]
