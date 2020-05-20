final-html-css
==============
Final project from http://webdesign.tutsplus.com/courses/30-days-to-learn-html-css done by myself.

It's a simple site (PSD design from ThemeForest): just HTML and CSS. Grid system 960gs is used.
Clickable links are: 'home', 'work examples'.

«Final HTML CSS» delpoyed: http://artkirienko.github.io/final-html-css

## Docker: Run web container

```bash
$ docker-compose up -d
```

It will build images and create containers and run them in background
to check status run `$ docker-compose ps`

Open http://localhost:3000 to test if app working properly

## Docker: How to stop the app?

```bash
$ docker-compose stop
```

## Docker: How to re-create containers?

```bash
$ docker-compose down && docker-compose up
```

## Docker: How to connect (ssh-like) to web app

```
$ docker-compose run web /bin/sh
```
