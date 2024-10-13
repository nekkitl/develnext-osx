###### В текущий момент в доработке. Репозиторий пока пуст.
<h1><img src="https://api.nekkit.xyz/github/dnide/app.png" width="256px"><br>
DevelNext OSX</h1>

<img src="https://api.nekkit.xyz/github/dnide/scr1.png" width="800px">

> **Имя:** DevelNext IDE \
> **Версия:** 16.7.2 \
> **Разработчик:** Дмитрий Зайцев \
> **Ссылка:** [DevelNext](https://develnext.org) \
> **JRE:** 1.8+ \
> \
> **Описание:** DevelNext IDE – это среда разработки, ориентированная на быстрое создание программ,
> простых 2D игр, функциональных прототипов под Windows/Linux/Mac. Инструментарий среды обеспечивает
> быстрый старт, легкость в освоении и обучении, он позволяет создавать десктопные программы с
> помощью языка PHP и различных мастеров и диалогов.

### Изменения

<p style="font-family: monospace">
 - Адаптировал и минимизировал интерфейс для macOS, чтобы он выглядел более
приятно и был более удобен в использовании.
<br> -  Создал тёмную тему, чтобы не резала глаза.
<br> -  Добился стабильной работы приложения.
<br> -  Распилил исходный код на несколько уровней.
<br> -  Нарисовал иконки в духе macOS
<br> -  Исправил маленькие ошибки в коде.
<br> -  Написал и доработал plist для macOS
<br> -  Исправлены лаунчер и плагины для запуска
<br> -  Система теперь знает расширения студии, а так же отображает соответсвующие иконки.
<br> -  Провел рефакторинг кода, что убрало некоторые проблемы.
<br> -  Создал Toolkit по сборке приложения.
<br> -  Реализовано автообновление приложения при запуске.
</p>

## Особенности

> <img src="https://api.nekkit.xyz/github/dnide/scr4.png" width="800px"/><br>
> **Легкость начала работы**:<br>
> DevelNext IDE настроен для быстрого старта. Вы можете начать создавать<br>
> свои программы, игры, прототипы без избыточных настроек.

> <img src="https://api.nekkit.xyz/github/dnide/scr5.png" width="800px"/><br>
> **Встроенные инструменты для разработчика**:<br>
> DevelNext IDE имеет встроенные инструменты, которые помогают в разработке,<br>
> таких как отладчик, профайлер, мастера создания различных типов проектов.

> <img src="https://api.nekkit.xyz/github/dnide/scr8.png" width="800px"/><br>
> **Понятный язык программирования**:<br>
> DevelNext IDE использует язык программирования jPHP. По сути - это PHP 7.4,
> язык программирования высокого уровня, который имеет огромное количество<br>
> готовых решений и библиотек.

> <img src="https://api.nekkit.xyz/github/dnide/scr9.png" width="800px"/><br>
> **Адаптация функций macOS:** <br>
> DevelNext IDE поддерживает macOS, например ее меню, кнопки и т.д. Нет проблем<br>
> cо сборкой и компилированием проекта.

## Скриншоты

<div style="display: grid; grid-template-columns: repeat(3, minmax(0, 1fr)); grid-gap: 10px;">
    <img src="https://api.nekkit.xyz/github/dnide/scr1.png" width="250px" alt="Загрузчик"/>
    <img src="https://api.nekkit.xyz/github/dnide/scr2.png" width="250px" alt="Воркспейс"/>
    <img src="https://api.nekkit.xyz/github/dnide/scr3.png" width="250px" alt="Меню загрузки или создания проектов"/>
    <img src="https://api.nekkit.xyz/github/dnide/scr4.png" width="250px" alt="Рабочая среда DevelNext OSX"/>
    <img src="https://api.nekkit.xyz/github/dnide/scr5.png" width="250px" alt="Редактор кода с комментариями"/>
    <img src="https://api.nekkit.xyz/github/dnide/scr6.png" width="250px" alt="Создание модулей"/>
    <img src="https://api.nekkit.xyz/github/dnide/scr7.png" width="250px" alt="Редактор стилей"/>
    <img src="https://api.nekkit.xyz/github/dnide/scr8.png" width="250px" alt="Модули IDE"/>
    <img src="https://api.nekkit.xyz/github/dnide/scr9.png" width="250px" alt="Демонстрация единого меню"/>
</div>

## Ссылки

#### Исходная среда разработки

- [Оригинальная DevelNext IDE](https://github.com/jphp-compiler/develnext)
- [JPHP](https://jphp.org)
- [JPHP-Compiler](https://github.com/jphp-compiler)

## Разработчикам

#### Для комфортной работы с исходным кодом:

```shell
brew install openjdk@8 fish jq php@7.4
```

Рекомендуемая среда для работы с исходным кодом: `IntelliJ IDEA 2024.1`

#### Режимы запуска:

<p style="font-family: monospace; "> 
В собранной версии есть несколько режимов запуска и отладки. <br>
В чем различия между ними? Первая использует штатный - <b>`LauncherFX`</b>, вторая - <b>`jphp-compiler`</b>.
</p>

- <p style="font-family: monospace; "> Основной запуск в <b>стандартном режиме</b>: </p>

  ```shell
  /Applications/DevelNext.app/Contents/MacOS/dnide
  ```

- <p style="font-family: monospace; "> Запуск в отладочном режиме с <b>использованием jphp-compiler</b>:</p>

  ```shell
  /Applications/DevelNext.app/Contents/MacOS/debugModes --php-runner
  ```


- <p style="font-family: monospace; "> Запуск в отладочном режиме с <b>использованием LauncherFX</b>:</p>

  ```shell
  /Applications/DevelNext.app/Contents/MacOS/debugModes --lfx
  ```

#### Ссылки:

<p style="font-family: monospace; ">
- <a href="https://docs.develnext.org">Документаця jPHP</a><br>
- <a href="https://www.php.net/manual/ru/">Документация PHP</a><br>
- <a href="https://vk.com/develnextstudio">Группа разработчиков в ВКонтакте</a><br>
</p>

#### Баг-репорты:

<p style="font-family: monospace; ">
Если вы нашли ошибку или баг, пожалуйста, подробно распишите о ней в `issue` на <br>
<a href="https://github.com/nekkitl/develnext-osx/issues">GitHub странице проекта</a>,
указав шаги которые привели к ошибке, и если возможно,<br>приложите скриншот.
</p>

#### Поддержка проекта:

<p style="font-family: monospace; ">
Если только моральная, а также идейная. <br>
Буду рад если Вы поставите звёзду проекту. Спасибо.
</p>


___

<p style="font-size: 11px; font-family: monospace; color: #666; ">
<a href="https://github.com/nekkitl/develnext-osx">DevelNext OSX</a> © 2023-2024
<br>Fork by Nick Ognev a.k.a <a href="https://me.nekkit.xyz">"nekkitl"</a>
</p>
