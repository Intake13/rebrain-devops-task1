# Таск 4

> Реппозиторий для задания4

В данном репозитории находится:
1. Файл README.md
2. Стандартный конфигурационный файл nginx

Реппозиторий доступен по ссылке [config](https://gitlab.rebrainme.com/devops_users_repos/3498/rebrain-devops-task1)

## Usage

![screenshot1](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fcheckroi.ru%2Fblog%2Fwp-content%2Fuploads%2F2020%2F06%2Fprofession-devops-engineer-e1591042905139.jpg&f=1&nofb=1)

###Добавьте данные блоки кода в ***nginx.conf*** чтобы включить поддержку

```nginx
mail {
  auth_http  _PATH_FOR_AUTH_;
  pop3_capabilities  "TOP"  "USER";
  imap_capabilities  "IMAP4rev1"  "UIDPLUS";

  server {
    listen     _PORT_;
    protocol   _PROTOCOL_;
    proxy      on;
  }

  server {
    listen     _PORT_;
    protocol   _PROTOCOL_;
    proxy      on;
  }
```
В следующие переменные нужно вписать свои значения:
* PATH_FOR_AUTH
* PORT
* PROTOCOL

```
hello warld
```

Название файла  | Содержание файла
----------------|----------------------
README.md       | Файл описания
nginx.conf      | Стандартный конфиг файл



## API

```js
var rebrainDevopsTask1 = require('rebrain-devops-task1')
```

See [api_formatting.md](api_formatting.md) for tips.

## Install

With [npm](https://npmjs.org/) installed, run

```
$ npm install rebrain-devops-task1
```

## Acknowledgments

rebrain-devops-task1 был вдохновлен командой REBRAIN

## See Also

- [`Readme Template`](https://github.com/hackergrrl/common-readme)
- [`Гайд по Markdown`](https://guides.github.com/features/mastering-markdown/)

## License

ISC

