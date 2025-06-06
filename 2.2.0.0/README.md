# Плагин Portmone.com для OpenCart-2.2.0.0

Creator: Portmone.com   
Tags: Portmone, OpenСart, payment, payment gateway, credit card, debit card    
Requires at least: OpenCart-2.2.0.0
License: Payment Card Industry Data Security Standard (PCI DSS) 
License URI: [License](https://www.portmone.com.ua/r3/uk/security/) 

Расширение для OpenСart позволяет клиентам осуществлять платежи с помощью [Portmone.com](https://www.portmone.com.ua/r3/).

### Описание
Этот модуль добавляет Portmone.com в качестве способа оплаты в ваш магазин OpenСart. 
Portmone.com может безопасно, быстро и легко принять VISA и MasterCard в вашем магазине за считанные минуты.
Простые и понятные цены, первоклассный анализ мошенничества и круглосуточная поддержка.
Для работы модуля необходима регистрация в сервисе.

Регистрация в Portmone.com: [Create Free Portmone Account](https://www.portmone.com.ua/r3/ecommerce/sign-up)    
С нами ваши клиенты могут совершать покупки в UAH.

### Ручная установка
1. Убедитесь в правильности версий модуля и вашей CMS OpenCart-2.2.0.0, они должны соответствовать.
2. Скачать плагин к себе на компьютер, распаковать.
3. Закачать все из папки upload в корневую папку OpenCart.

### Настройка модуля
1.  Зайти в админ-панель, найти в списке меню Дополнения->Платежи метод оплаты Portmone и нажать "Установить"
2.  Перейти на вкладку Редактировать, выбрать "Включить прием оплаты через Portmone"->Включить
3.  Заполните:
    - «Идентификатор магазина в системе Portmone(Payee ID)»;
    - «Логин Интернет-магазина в системе Portmone»;
    - «Пароль Интернет-магазина в системе Portmone»;    
    - «Ключ для подписи данных, должен быть занесен в систему Portmone»;
    Эти параметры предоставляет менеджер Portmone.com;    
    - «Время на оплату выставляется в секундах»;
    - прочие поля заполните по своему усмотрению.
4. Нажмите кнопку «Сохранить».

Метод активен и появится в списке оплат вашего магазина.    
P.S. Portmone, принимает только Гривны (UAH).   
P.S. Сумма платежа не конверируется в валюту Гривны(UAH) автоматически. В магазине по умолчанию должна быть валюта Гривны (UAH).
