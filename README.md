[![CircleCI][circle-image]][circle-url]
## Description

* Elasticsearch usage example
* Autocomplete control developed with angular 2

##First of all
* Install elasticsearch server according to the [instructions](https://www.elastic.co/guide/en/elasticsearch/reference/current/_installation.html).
* Add this lines to your elasticsearch.yml configuration file (it's not recommended in real app):

```yml
http.cors.enabled : true 
http.cors.allow-origin : "*"
http.cors.allow-methods : OPTIONS, HEAD, GET, POST, PUT, DELETE
http.cors.allow-headers : X-Requested-With,X-Auth-Token,Content-Type, Content-Length
```

## Quick start
Install:
```bash
npm install -g webpack webpack-dev-server
npm install
```
Build:
```bash
npm run build
```
Start in dev mode (available on [localhost:8080](localhost:8080) by default)
```bush
npm run dev
```
Follow this steps: 
1. Go to admin tab and add something to the elasticsearch index using provided form
2. Go back to the client page
3. Search! (performed by title field by default)

[circle-image]: https://circleci.com/gh/byavv/angular2-elastic.svg?style=shield
[circle-url]: https://circleci.com/gh/byavv/angular2-elastic