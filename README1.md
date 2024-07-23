# Разработка смарт-контракта для управления идентификационными данными и предоставления доступа к ним.

## Ход выполнения проекта, поясняющие скриншоты отражающие процесс выполнения и создания проекта

#### Разворачиваем Ganache

<image src="img\Ganache.png" alt="wind">
<image src="img\Ganache port.png" alt="wind">

Для Metamask нужен один из приватных ключей!

Очень важно, чтобы порт на котором был развёрнут Ganache был 8545 и сеть 1337. Точно как в файле truffle-config.js!!!

#### Осуществляем миграцию и деплой смарт-контракта

Если контракт не разворачивается, нужно проверить порт в cmd

<image src="img\Порты - проблема!.png" alt="wind">

Осуществляем компиляцию контракта

<image src="img\Компиляция truff.png" alt="wind">

Миграция и деплой контракта

<image src="img\Инициация миграции.png" alt="wind">

<image src="img\Деплой.png" alt="wind">

Внимание! Сеть: 1337 - Ganache
Для Metamask нужен адрес контракта!

#### Подключение Metamask

<image src="img\Токен импортирован.png" alt="wind">

Показано создание нового счёта в Metamask и импорт ключа

<image src="img\Состояние Metamask.png" alt="wind">

К сожалению - это временно!

#### Развёртывание React приложения

<image src="img\Установка React.png" alt="wind">

<image src="img\Установка React2.png" alt="wind">

<image src="img\Разворачивание приложения.png" alt="wind">

Страничка для регистрации смарт-контракта

<image src="img\Страничка загрузки!.png" alt="wind">

#### Подключение Metamask к сайту
<image src="img\Подключение к сайту.png" alt="wind">

Регистрация

<image src="img\Рег.png" alt="wind">

#### Подключение сервера

<image src="img\Разворачивание контракта.png" alt="wind">

<image src="img\Разворачивание приложение на сервере.png" alt="wind">

<image src="img\Сообщение с сервера.png" alt="wind">



