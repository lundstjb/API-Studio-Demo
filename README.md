## Install the swagger module

Install using npm. For complete instructions, see the [install](./docs/install.md) page.

```bash
$ npm install -g swagger
```

## Design your API in the Swagger Editor

The interactive, browser-based [Swagger Editor](http://editor.swagger.io/) is built in. It provides Swagger 2.0 validation and endpoint routing, generates docs on the fly, and consumes easy-to-read YAML.

```bash
$ swagger project edit
```

## Run the server

Run the project server.

```bash
$ swagger project start
```

## Now, call the API!

It just works!

```bash
$ curl http://127.0.0.1:10010/hello?name=Scott
"Hello, Scott!"
```
