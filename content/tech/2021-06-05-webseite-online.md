---
title: "Webseite online"
slug: "webseite-online"
page: true
thumbnail_hide_post: false
date: 2021-06-05
lead: Statisch aufgeladen
---

Unsere Webseite ist in einer rudimentären Version online gegangen.
Wir nutzen einen statische Webseitengenerator names [Hugo](https://gohugo.io/) - das tolle daran ist dass man keinen Webserver brauch, keine Datenbank - es reicht die Webseite einfach in einen Dateneimer (S3 Bucket) zu werfen und ihn als Webseite zu nutzen.

Wer mag, kann sich unsere Webseite auf seinem Rechner ([Github link](https://github.com/boeddenstedt/boedde-net-website)) anschauen und erweitern.

```bash
git clone --recurse-submodules https://github.com/boeddenstedt/boedde-net-website.git
cd boedde-net-website
```

Anschliessend hugo installieren ([hier die Anleitung](https://gohugo.io/getting-started/installing/)) und los geht es.

```bash
$ hugo serve 
Start building sites …

                   | DE
-------------------+-----
  Pages            | 10
  Paginator pages  |  0
  Non-page files   |  4
  Static files     | 39
  Processed images |  0
  Aliases          |  2
  Sitemaps         |  1
  Cleaned          |  0

Built in 43 ms
Watching for changes in /Users/kniepbert/Daten/temp/boedde-net-website/{archetypes,content,layouts,static,themes}
Watching for config changes in /Users/kniepbert/Daten/temp/boedde-net-website/config.toml
Environment: "development"
Serving pages from memory
Running in Fast Render Mode. For full rebuilds on change: hugo server --disableFastRender
Web Server is available at http://localhost:1313/ (bind address 127.0.0.1)
Press Ctrl+C to stop
```

Unter [localhost:1313](http://localhost:1313/) kann man nun die Webseite bestaunen.