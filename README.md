# Opencart

 Плагин: InterKassa Gateway
 Описание: Платежный шлюз "Интеркасса" для сайтов Open Cart 2.0-2.1-2.2 (версия протокола Интеркассы 2.0)
 Предназначение: Модуль добавляет способ оплаты "Интеркасса" для Open Cart 2.0-2.1-2.2
 Версия: 3.3
 Последнее обновление: 12.06.2017

 
 -#Установка
 1. Убедитесь в соответствии версий модуля и вашей CMS, они должны совпадать.
 2. Скачать плагин к себе на компьютер, распаковать
 3. Закачать все из папки upload на сервер
 4. зайти в админку, найти в списке метод оплаты "InterKassa" и нажать "Активировать"
 5. Перейти на вкладку настроек, заполнить все поля, уникальный номер кошелька, секртеный ключ, тестовый ключ при необходимости.
 6. Можете воспользоваться нашим новым API. Для этого возьмите id и key с настроек вашего аккаунта , вкладка API. 
   Также вам необходимо добавить IP(айпи) вашего сайта в поле IP фильтр. 
   
 Узнать свой айпи можно в любом интернет-сервисе "айпи сайта" или в консоли вашей операционной системы наберите:
 ping адрес вашего сайта 
 например:
 ping interkassa.com
 Жмем "Сохранить"
 Метод активен и появится в списке оплат вашего магазина.
 
 P.S. Для тестирования платежей в кассе используйте тестовую валюту XTS (тестовая платежная система), для это необходимо включить в кассе этот пункт, и далее при перенаправлении на сайт "Интеркассы" выбрать ее в качестве оплаты, далее система сгенерирует тестовую страничку со всеми видами ответа от сервера, это поможет вам настроить все необходимые параметры и убедиться в работоспособности вашей системы.