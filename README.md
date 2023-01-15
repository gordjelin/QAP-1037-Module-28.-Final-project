# QAP-1037-Module-28.-Final-project
===========================================

Задание следущее:

Протестировать требования.
Разработать тест-кейсы (не менее 15). Необходимо применить несколько техник тест-дизайна.
Провести автоматизированное тестирование продукта (не менее 15 автотестов). Заказчик ожидает по одному автотесту на каждый написанный тест-кейс. Оформите свой набор автотестов в GitHub.
Оформить описание обнаруженных дефектов. Во время обучения вы работали с разными сервисами и шаблонами, используйте их для оформления тест-кейсов и обнаруженных дефектов. (если дефекты не будут обнаружены, то составить описание трех дефектов)

===========================================

Проект содержит файлы необходимые для проведения тестирования нового интерфейса авторизации в личном кабинете от заказчика Ростелеком Информационные Технологии.

===========================================
В файле 28 Module T-K Full.xlsx содержится набор тест-кейсов и баг-репорты
===========================================
Папка pages содержит 2 файла:
  base_page.py - содержит базовый класс страницы
  authtorization_page.py - содержит класс для страницы авторизация
  
Папка test_data содержит 4 файла: 
  invalid_data.py - содержит валидные данные для тестов
  valid_data.py - содержит НЕвалидные данные для тестов
  locators.py - содержит локаторы тестируемой страницы
  messages.py - содержит сообщения об ошибках
  
Папка tests содержит 2 файла: 
  conftest.py - содержит функцию вебдрайвера
  tests_all_pages.py - содержит автотесты
  
===========================================
