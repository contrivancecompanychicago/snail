# Snail

simulate wireless network, powered by [Node.js](http://nodejs.org).

## Features

- all with only one command


## Install

``` bash
npm install -g snail
```

## Update

``` bash
npm update -g snail
```

## Getting Started

simulate 3g network:

``` bash
snail 3g
```

simulate 2g netword:

``` bash
snail 2g
```

simulate what you want:

``` bash
snail 160 170 400 8080
```
the command mean:
* bandwidth_down=160 kbps
* bandwidth_up=160 kbps
* delay=400ms
* port=8080

##Default
- 2G snail 80 80 800 9105
- 3G snail 160 160 400 9105

## Next Step

add windows.performance.timing  statistics

## Contributors
* [@mdemo](http://weibo.com/mdemo)
* [commenthol](https://github.com/commenthol)
* liuchen

##License
(The MIT License)

Copyright (c) 2013 [@mdemo](http://weibo.com/mdemo) and other contributors
