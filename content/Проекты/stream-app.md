---
tags:
  - typescript
  - javascript
  - web
  - angular
  - python
  - server
title: 📺Stream App
---
# [📺GitHub Stream App](https://github.com/Kanzu32/angular-stream-app)

## Описание
Веб-приложение для обреки релевантных участков видеострима.

Трансляция видео по протоколу UDP или HTTP с использованием Python и ffmpeg. Поддерживаются следующие форматы:
* MPEGTS: Транспортный поток MPEG;
* MPEG1VIDEO: Видео MPEG-1;
* MPEG2VIDEO: Видео MPEG-2;
* XVID: Видео Xvid;
* DASH: Dynamic Adaptive Streaming over HTTP (DASH).

Серверная часть получает стрим, записывает и ретранслирует его в веб приложение в формате DASH а также редактирует по команде пользователя с использованием Python, Flask и ffmpeg.

Клиентская часть на Angular выводит стрим пользователю, предоставляет возможность начать или остановить запись, скачать, обрезать и просмотреть записанные файлы на сервере.

## Особенности
* Трансляция в разных форматах;
* Запись видео из стрима;
* Выбор записанного видео из списка;
* Обрезка видео;
* Преобразование форматов стримов и видео;
* Скачивание видео с сервера.

## Технологии
* JavaScript;
* TypeScript;
* HTML;
* CSS;
* Python;
* ffmpeg;
* Angular.

## Скриншоты
![[stream-1.png]]
![[stream-2.png]]
![[stream-3.png]]
![[stream-4.png]]
![[stream-5.png]]
