[![SurvShell Logo](https://github.com/Kristina1996/surv-shell/blob/master/resources/64x64.png)](https://github.com/Kristina1996/surv-shell/)[![Angular Logo](https://www.vectorlogo.zone/logos/angular/angular-icon.svg)](https://angular.io/) [![Electron Logo](https://www.vectorlogo.zone/logos/electronjs/electronjs-icon.svg)](https://electronjs.org/)

[![Make a pull request][prs-badge]][prs]
[![License](http://img.shields.io/badge/Licence-MIT-brightgreen.svg)](LICENSE2.md)

# Введение

Настольное Angular/Electron/SASS-приложение для создания и редактирования Excel-отчётов для одной Системы управления рабочим временем (СУРВ), основанное на шаблоне https://github.com/maximegris/angular-electron.git.

## Разработчикам

Для внесения правок в проект выполните следующие шаги:

* Авторизуйтесь на GitHub
* Сделайте fork репозитория (подробнее в ["About forks"](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-forks))
* Клонируйте fork'нутый репозиторий на свой локальный компьютер:

``` bash
git clone https://github.com/<your-github-account-name>/surv-shell.git
```

* Установите Node, если требуется
* Установите зависимости с помощью npm:

``` bash
npm install
```

* При необходимости глобально установите @angular/cli с помощью команды:

``` bash
npm install -g @angular/cli
```

* Создайте ветку типа ```issue/<issue-number>```
* Закачайте изменения на GitHub и создайте pull request в [репозиторий SurvShell](https://github.com/Kristina1996/surv-shell) (Подробнее в ["Creating a pull request from a fork"](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request-from-a-fork))

## Сборка, запуск и разработка приложения

|Команда|Описание|
|--|--|
|`npm start`| Сборка приложения и запуск его для разработки |
|`npm run electron:linux`| Сборка приложения под Linux |
|`npm run electron:windows`| Сборка приложения под Windows 32/64 bit |

Остальные команды см. в файле ```package.json```. 

## Обратная связь

https://github.com/Kristina1996/surv-shell/issues

[license-badge]: https://img.shields.io/badge/license-Apache2-blue.svg?style=flat
[license]: https://github.com/Kristina1996/surv-shell/blob/master/LICENSE2.md
[prs-badge]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square
[prs]: http://makeapullrequest.com
