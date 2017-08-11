# bootstrap-select-ajax

Notice: This package is forked from [silviomoreto/bootstrap-select](https://github.com/silviomoreto/bootstrap-select). I just modify a little code for ajax(at line 1426 in js/boostrap-select-ajax.js).And i add a stamp.

## Install

> npm install bootstrap-select-ajax

## HTML

```html
<select class="ajax-search" ajax-url="your ajax api" ajax-params="{#pnType#: #onePart#, #fromSys#: #scmship#}" ajax-option-name="name" ajax-option-value="age" default-data="{#name#: #xiaoming#, #age#: 28}"></select>
```

## Attribute description

|Attribute|type|description|
|---------|----|-----------|
|ajax-search-key|string|search key
|ajax-url|string| request url
|ajax-params|like json |use # instead ", request other params
|ajax-option-name|string|option's name
|ajax-option-value|value|option's value
|default-data|like json|use # instead " ,corresponding ajax-option-name and ajax-option-value

## How to use

1.npm install

2.gulp

3.open [http://localhost:8080](http://localhost:8080) in your chrome brower

4.you will see demo