# goit-advancedjs-hw-05

Homework for the Intro to TypeScript topic.

## Task

Потрібно встановити та налаштувати середовище розробки. 

Усі детальні кроки
описані в роздiлах конспекту 4-6.

### Brief description of actions

1. Створи репозиторій на GitHub під назвою `goit-advancedjs-hw-05`.
1. Налаштуй середовище розробки (Тема  "Встановлення та налаштування середовища розробки").
1. Налаштуй компілятор (Тема "Налаштування компілятора").
1. Встанови `source maps в tsconfig.json` у проєкті TypeScript для налагодження коду у браузері (Тема 9.6 “Debugging”).

## Acceptance Criteria

* Створено репозиторій `goit-advancedjs-hw-05`.
* Домашня робота містить посилання на робочу сторінку на `GitHub Pages`.
* До роботи прiкрiплено файл репозиторiю у форматi `zip`.
* Коректно налаштоване середовище розробки.
* Коректно налаштований компілятор.
* Встановлено `source maps` в `tsconfig.json` у проєкті TypeScript.

### How-To init TypeScript project from scratch

* [Nodejs](https://nodejs.org/en/) (preferably latest LTS version).
* Run `npm install -g typescript` to install TypeScript using npm.
* Run `tsc --init` to initialize a TypeScript project and create a `tsconfig.json` file.
* Set up project config in `tsconfig.json` file, including `sourceMap` option for debugging in browser.
* Run `tsc` to compile manualy using The TypeScript Compiler.
* Run `tsc -w` to watch changes in TypeScript files and compile them as you you save them.
* Run `npm init -y` to to set up npm package and create `package.json` config file.

### How-To run TypeScript project

* Run `npm i --save-dev @web/dev-server` to install local web server
* In `package.json` config file add `"start": "web-dev-server --node-resolve --open --watch"` option to `"scripts"` section to setup how to start web sever.
* Run `npm start` to start web server. You will be provided with URL, where the project is awailable.