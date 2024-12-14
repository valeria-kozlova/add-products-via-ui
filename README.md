# Автоматизация тестирования системы управления товарами QualIT 
## 📄 Описание
Проект предназначен для автоматизации тестирования веб-интерфейса системы управления товарами QualIT. Реализованы тесты для добавления новых товаров через UI, 
включая экзотические и не экзотические фрукты и овощи. Все операции выполняются с помощью Selenium WebDriver.

## 🛠 Технологии
- Java, JUnit 5
- Selenium WebDriver
- Maven
## 📂 Структура проекта
- pages/ — классы Page Object
- tests/ — тестовые сценарии
## 🚀 Установка
1. Клонируйте проект:
```bash
git clone https://github.com/valeria-kozlova/add-products-via-ui
```
2. Настройте chromedriver.
3. Запустите тесты через Maven или IDE.
## 🔌Подключение к стенду
1. Создайте папку Working Project на диске C.
2. Скачайте .jar файл по [ссылке](https://drive.google.com/file/d/18bI8rR9uPjVUNbSPIXBs84qViW0_VFpg/view).
3. Скопируйте скачанный файл в созданную папку.
4. Откройте консоль cmd.exe и переключитесь в папку с файлом командой:
```bash
cd C:\Working Project
```
5. Запустите стенд с помощью команды:
```bash
java -jar qualit-sandbox.jar
```
6. Перейдите по адресу: http://localhost:8080.
7. Для работы со стендом используйте вкладку "Песочница" - "Товары".
## 🌟 Функционал
- Добавление товаров через UI.
- Проверка добавления экзотических и не экзотических фруктов и овощей.
- Интеграция с веб-интерфейсом.