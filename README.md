Чтобы собрать и запустить проект:

1. Должен быть установлен [Yarn](https://yarnpkg.com) (требует установленный [node.js](https://nodejs.org)).

2. В командной строке, находясь в папке с проектом, нужно выполнить команду: `$ yarn`.

3. Затем, после установки всех пакетов:
  - `$ gulp build` — чтобы просто собрать проект. В корне проекта появится папка build, в которой будет вся вёрстка в HTML/CSS/JS формате.
  - `$ gulp dev` — чтобы собрать проект и запустить его на локальном сервере. После запуска в браузере должна автоматически открыться страница с собранным проектом (обычно это [http://localhost:3000](http://localhost:3000)).