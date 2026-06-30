- название проекта  AI
- Цель: запустить локально ИИ и понять как с ним работать и надо ли это вообще
- СТЕЙКХОЛДЕР: Я
- СРОКИ: не оговорены
- РЕСУРСЫ: 
ноутбук xiaomi,
 интернет c vpn, 
Я,
программное обеспечение:
ОС ubuntu 
средства мониторинга hw: локальный Prometheus+ grafana
    - ход проекта
    -  статус 3006
    -  проведен эксперимент1
    -  и эксперимент2
    - ВЫВОДЫ: нагрузка увеличивается, зависимость непонятна.
       - пришлось заново разворачивать модель на ноутбук
      ![ollama](https://github.com/Romanru5116/AI/blob/0b0986d82ce764f6af3abea756e4e2f215a85188/PIC/Screensho%D0%B5Ollama%20InsxtallAgain%20from%202026-06-30%2018-14-52.png)
  
    - статус 2906
      добавленматериал как писать агента для ИИ
      ![развернули другую модель](https://github.com/Romanru5116/AI/blob/96b5152db7dec6b88bf58a0da7407edd6aaf7994/PIC/ScreenshotOllamaInstall%20from%202026-06-29%2014-18-03.png)
    -  статус 2606
  n -   пытаемся ставить web UI
    -  ![как](https://github.com/Romanru5116/AI/blob/2acaa6836cd4fcb16d45db99708b1d7b38db9b76/PIC/ScreenshotOpenwebHow%20from%202026-06-26%2011-13-44.png)
    -  результат Не достигнут- порт занят графана
    -  ![результат](https://github.com/Romanru5116/AI/blob/8d8600a6041519e54f6adb12d2e6a730c0048e0a/PIC/ScreenshotWEbUI_portBusy%20from%202026-06-26%2011-29-54.png)
  
    - статус 2406
заключение: 
"какой-то очень простой ИИ - в основном отсылка на поискать в инете что интересует- взгляд как бы не помощника, а наблюдателя со стороны за пользователем. 
придется искать видимо другую llM- deepseek или gemini в инете которые-выглядят поинтереснее"
обновлен список материалов 
     - статус: 2406
игрался с консольным вводом,вывод:надо искать модельку посвежее, ответы имеющейся версии больше описательные типа "можно погуглить по таким словам"
    - СТАТУС: 2306
развернута платформа ollama и над ней LLM gamma -толстая порядка 13ГБ

![работакомандстатус](https://github.com/Romanru5116/AI/blob/8e2abfd968d3d5b236a5ea0bb5e7fb4002e788a4/PIC/Screenshot%20Ollamacommandfrom%202026-06-23%2017-16-01.png)

![развертывание](https://github.com/Romanru5116/AI/blob/8e2abfd968d3d5b236a5ea0bb5e7fb4002e788a4/PIC/Screenshot%20Ollama1%20from%202026-06-23%2000-51-57.png)

![развертывание](https://github.com/Romanru5116/AI/blob/8e2abfd968d3d5b236a5ea0bb5e7fb4002e788a4/PIC/Screenshot%20Ollama2%20from%202026-06-23%2001-42-04.png)

- материалы:
как ставить по шагам:
https://www.dmosk.ru/miniinstruktions.php?mini=ollama-llm-linux
![схема ИИ с агентами](https://github.com/Romanru5116/AI/blob/116dad261155030e8581cf35397f27835f3b8cf2/PIC/Screenshot_2026-06-24-09-55-46-424_com.deepseek.chat.jpg)

как написать агента
https://qwenlm.github.io/qwen-code-docs/ru/blog/thinks-like-a-programmer/
несколько картинок в pic
материалы web_ui
Совет 1. В Open WebUI можно поставить любую модель для Ollama из списка поддерживаемых
Для этого достаточно перейти по ссылке https://ollama.com/library и с помощью поисковой строки найти нужную модель. Если в названии модели нет префикса до /, значит она загружена разработчиками Ollama и проверена на работоспособность, если есть — эта модель загружена сообществом.
_
    -материалы общих знаний про суть ИИ- токены и вот это вот все просто и наглядно 
https://youtu.be/sSAIC8GQRe8?si=nSQWdonwxIH6AH4Q


