#  Ваш личный архив результатов тренировок!

**ProTimer.club** — это современное решение для спортсменов, позволяющее с высокой точностью измерять время, регистрировать результаты и анализировать их для повышения эффективности тренировок. Наши устройства подходят для различных видов спорта и соревнований, предоставляя пользователям удобство, точность и интеграцию с облаком.

Вы можете войти с демо-профилем и попробовать все возможности сайта прямо сейчас: https://protimer.club/login#demo

    Email: demo@protimer.club
    Password: demo 

А вот пример того, как вы можете делиться своей страницей и показывать свои результаты всем, даже незарегистрированным пользователям: https://protimer.club/share/MzlLRDlaT1hnMTNaeEVZbnFSTTNHUT09

<p align="center">
<a href="https://www.youtube.com/watch?v=7RWEwh4FOdk&list=PL6NJTNxbvy-KKb5Vj-JgzeaAFMx-zqKtX"><img src="https://github.com/renat2985/protimer.club/blob/main/doc/intro.png" height="400px"><img src="https://protimer.club/assets/img/photo/gg-07670-min.png" height="400px"></a>
</p>

## Основные функции

  -	**Точное измерение времени:** точность до 0,003 секунды.
  -	**Удобство использования:** простая настройка системы, доступная каждому.
  -	**Интеграция с облаком:** экспорт данных в облако ProTimer.club для хранения и анализа истории результатов.
  -	**Социальная сеть:** делитесь своими достижениями и следите за результатами друзей.
  -	**Многофункциональность:** поддержка различных режимов работы и возможностей для командных и индивидуальных тренировок.

_Почитать подробне о функциях, вы можете [здесь](https://protimer.club/ru/doc)._


## Как это работает

### Master Point — это главный модуль системы, который управляет всей сетью устройств ProTimer.

1.	**Включение и подключение:**
     
    - Включите Master Point, он создаст Wi-Fi сеть "ProTimer.club".
    - Подключитесь к этой сети с помощью смартфона, планшета или ноутбука.

        <img src="https://github.com/renat2985/protimer.club/blob/main/doc/wifi.png" height="300px">
 
2.	**Доступ к управлению:**
 
    - Откройте браузер и введите адрес `http://192.168.4.1` для доступа к веб-интерфейсу.
    - Используйте интерфейс для настройки режимов работы, управления таймером и экспорта данных.

        <img src="https://github.com/renat2985/protimer.club/blob/main/doc/AP.png" height="400px"> <img src="https://github.com/renat2985/protimer.club/blob/main/doc/AP3.png" height="400px">

3.	**Подключение к роутеру:**

    - При первом включении устройство запросит данные вашей домашней Wi-Fi сети: название роутера и пароль. Это необходимо для автоматического экспорта данных в облако.
    - После настройки устройство будет автоматически подключаться к указанному роутеру каждый раз при включении и выгружать данные в облако ProTimer.club.
    - Таким образом, после тренировки вам нужно всего лишь включить устройство на несколько секунд — оно само подключится к Wi-Fi и экспортирует все ваши результаты. Это просто и удобно!

    **Дисплей устройства:**

    <img src="https://protimer.club/assets/img/doc14.png" height="100px"> <img src="https://protimer.club/assets/img/doc13.png" height="100px"> <img src="https://protimer.club/assets/img/doc25.png" height="100px"> <img src="https://protimer.club/assets/img/doc15.png" height="100px">

    _Подробней можно почитать [здесь](https://protimer.club/ru/doc#doc5)._

### Point PRO — это дополнительный модуль, который может выполнять функции старта, промежуточной точки или финиша.

1.	**Режимы работы:**

    - Старт: запускает таймер при пересечении луча между датчиком и отражателем.
    - Промежуточный: фиксирует время прохождения между точками.
    - Финиш: останавливает таймер при пересечении луча.

3.	**Подключение к Master Point:**

    - Point PRO автоматически синхронизируется с Master Point на расстоянии до 250 м.
    - Используйте встроенный дисплей Point PRO для проверки связи и выбора режима.

3.	**Особенности Point PRO:**

    - Оснащен дисплеем для отображения текущего состояния.
    - Поддерживает переключение между несколькими каналами, что позволяет использовать несколько комплектов на одной трассе.
    - Высокая точность измерения — до 0,003 секунды.

    **Дисплей устройства:**

    <img src="https://protimer.club/assets/img/doc23.png" height="100px"> <img src="https://protimer.club/assets/img/doc22.png" height="100px"> <img src="https://protimer.club/assets/img/doc24.png" height="100px">

    _Подробней можно почитать [здесь](https://protimer.club/ru/doc#doc5)._

#### ⚠️ Point PRO и Master Point работают в связке, обеспечивая спортсменам и тренерам полный контроль над тренировками и точность результата.


## Контакты

Вы можете собрать устройство самостоятельно или попросить это сделать для вас. Для заказа готового устройства свяжитесь через [Telegram](https://t.me/ESPiotDevice), [WhatsApp](https://chat.whatsapp.com/H7IpCrilF00H3wGbANnA1i), [Skype](https://skype:renat2985?chat), [Discord](https://discord.gg/3986vwEdf5).

Так же на сайте представлены готовые комплекты оборудования с возможностью индивидуальной настройки и добавления модулей.


## Схема подключения
Вы можете собрать устройство на базе NodeMCU ESP8266 или Wemos ESP8266. Эта схема подходит к Master устройству и Point (PRO). Просто выберите нужный линк для утановки програмного обеспечения ниже.

На плате NodeMCU кнопка Flash выполняет те же функции, что и внешняя кнопка, подключенная к D3. При необходимости вы можете использовать её вместо внешней кнопки.

## Pinout Configuration

| **Pin** | **GPIO** | **Function**              |
|---------|----------|---------------------------|
| **D1**  | GPIO5    | SCK (Display)             |
| **D2**  | GPIO4    | SDA (Display)             |
| **RX**  | GPIO3    | IR or LASER Sensor        |
| **D3**  | GPIO0    | Button                    |
| **D7**  | GPIO13   | Active Buzzer (optional)  |
| **D6**  | GPIO12   | Passive Buzzer (optional) |
| **D0**  | GPIO16   | [GATE Relay](https://github.com/renat2985/protimer.club/discussions/6)                 |


### [E3Z-R61](https://www.aliexpress.com/item/1005004123351251.html) (max 2-3м "ворота", ИК-датчик)

<img src="https://github.com/renat2985/protimer.club/blob/main/doc/schematic.png" height="200px" alt="Connection Diagram"> <img src="https://github.com/renat2985/protimer.club/blob/main/doc/schematic2.png" height="200px" alt="Connection Diagram 2"> 

### [E3Z-LAS-R8, NPN NO](https://www.aliexpress.com/item/1005005879848648.html) (max 7-8м "ворота", лазерный датчик)

<img src="https://github.com/renat2985/protimer.club/blob/main/doc/schematic3.png" height="200px" alt="Connection Diagram 3"> <img src="https://github.com/renat2985/protimer.club/blob/main/doc/schematic4.png" height="200px" alt="Connection Diagram 4">

## STL (stl папка)

Все эти детали вы можете найти и распечатать в папке stl. 

<img src="https://github.com/renat2985/protimer.club/blob/main/stl/box-big.png" height="200px" alt="Box big"> <img src="https://github.com/renat2985/protimer.club/blob/main/stl/box-small.png" height="200px" alt="Box small"> <img src="https://github.com/renat2985/protimer.club/blob/main/stl/сover-microUSB.png" height="200px" alt="Cover MicroUSB"> <img src="https://github.com/renat2985/protimer.club/blob/main/stl/сover-сable.png" height="200px" alt="Cover cable"> <img src="https://github.com/renat2985/protimer.club/blob/main/stl/mirror3.png" height="200px" alt="Reflector Holder 3"> <img src="https://github.com/renat2985/protimer.club/blob/main/stl/mirror4.png" height="200px" alt="Reflector Holder 4"> <img src="https://github.com/renat2985/protimer.club/blob/main/stl/mirror5.png" height="200px" alt="Reflector Holder 5">


<img src="https://github.com/renat2985/protimer.club/blob/main/doc/IMG_0487.jpg" height="100px" alt="Photo 1"> <img src="https://github.com/renat2985/protimer.club/blob/main/doc/IMG_0488.jpg" height="100px" alt="Photo 2"> <img src="https://github.com/renat2985/protimer.club/blob/main/doc/IMG_0489.jpg" height="100px" alt="Photo 3">

## AliExpress.com

[E3Z-R61](https://www.aliexpress.com/item/1005004123351251.html) (2-3м, ИК-датчик) или [E3Z-LAS-R8, NPN NO](https://www.aliexpress.com/item/1005005879848648.html) (7-8м, лазерный датчик)

[Reflector TD-05](https://www.aliexpress.com/item/32990489226.html) (Лучше) или [Reflector TD-08](https://www.aliexpress.com/item/1005003584568763.html) (Хуже)

[I2C SSD1315 128x64 1.3inch](https://www.aliexpress.com/item/1005004118377699.html)

[Wemos MINI ESP07](https://www.aliexpress.com/item/1005007081723288.html) (потходит для STL корпуса) или [NodeMCU ESP8266](https://www.aliexpress.com/item/1005004893349830.html)

[Push Button Switch](https://www.aliexpress.com/item/1005004159746274.html)

[Passive Buzzer Shield for WEMOS (D6 gpio)](https://www.aliexpress.com/item/1005007463046770.html) or [Active Buzzer Module for Arduino (D7 gpio)](https://www.aliexpress.com/item/1005005528181661.html)

[Power Bank for 18650 Battery](https://www.aliexpress.com/item/1005002367815544.html)

[Mini Flexible Sponge Octopus Tripod](https://www.aliexpress.com/item/1005004177317958.html)

Дополнительные компоненты для E3Z-LAS-R8, NPN NO

[Step-Down Board Mini 360](https://www.aliexpress.com/item/1005005995617482.html)

[Mini DC Boost Converter Board](https://www.aliexpress.com/item/1005007013856492.html)

[1N4728A 3.3V Zener Diode](https://www.aliexpress.com/item/4000297831644.html)

---

### 🚀 **Веб-установщик (рекомендуется)**  
Настройте устройство легко и быстро с помощью веб-установщика. Выберите подходящую версию и следуйте инструкциям.

- **[Master Installer](https://renat2985.github.io/protimer.club/):** Главное устройство, которое будет запоминать время.  
- **[Point Installer](https://renat2985.github.io/protimer.club/point.html):** Дополнительное устройство, которое фиксирует финиш, промежуточные точки или старт.  

---

## :battery: Donation

If you like this project, you can buy me a cup of coffee :coffee:

<img src="https://github.com/renat2985/renat2985/raw/main/donate/donate.png" width="100%">

- PayPal [https://www.paypal.me/RKevrels](https://www.paypal.me/RKevrels/5)