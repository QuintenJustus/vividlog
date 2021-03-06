<img src="https://gitlab.com/QuintenJustus/vividlog/raw/master/assets/logo.png" alt="Vivid Log"/>

[![npm version](https://badge.fury.io/js/vividlog.svg)](https://badge.fury.io/js/vividlog) ![npm](https://img.shields.io/npm/dm/vividlog.svg) [![CircleCI](https://circleci.com/gh/QuintenJustus/vividlog.svg?style=svg)](https://circleci.com/gh/QuintenJustus/vividlog) [![Maintainability](https://api.codeclimate.com/v1/badges/11d9beceb62db9ab9ef1/maintainability)](https://codeclimate.com/github/QuintenJustus/vividlog/maintainability) [![DeepScan grade](https://deepscan.io/api/teams/3510/projects/5183/branches/40300/badge/grade.svg)](https://deepscan.io/dashboard#view=project&tid=3510&pid=5183&bid=40300) [![Test Coverage](https://api.codeclimate.com/v1/badges/11d9beceb62db9ab9ef1/test_coverage)](https://codeclimate.com/github/QuintenJustus/vividlog/test_coverage) 

> Ever thought the native console logging feature could be better?

This npm module makes it slightly easier but mainly a lot nicer to log to the browser console.

## Installation & Usage
#### Install with npm
Installation is as simple as any other npm module.<br>
```bash
npm i vividlog --save-dev
```

#### Install with CDN
Or add this to your html file directly <br>
```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/npm/vividlog@latest/dist/vividLog.js"></script>
```

>#### Usage
>##### Available methods
>  Note that VividLog is bound to `window.vividLog`<br>
<img src="https://gitlab.com/QuintenJustus/vividlog/raw/master/assets/functions.png" width="650">

>##### Configuration
<img src="https://gitlab.com/QuintenJustus/vividlog/raw/master/assets/config.png" width="650">

## Preview - more images coming soon
#### What you can expect
<img src="https://gitlab.com/QuintenJustus/vividlog/raw/master/assets/withconsole.png"
     alt="Vivid Log" height="500" style="border-radius:5px; box-shadow: 1px 3px 5px black"/>

#### Without grouping and with grouping
<img src="https://gitlab.com/QuintenJustus/vividlog/raw/master/assets/groupedandwithout.png"
     alt="Vivid Log" style="border-radius:5px; box-shadow: 1px 3px 5px black"/>

#### Expanded group
<img src="https://gitlab.com/QuintenJustus/vividlog/raw/master/assets/grouped.png"
     alt="Vivid Log" style="border-radius:5px; box-shadow: 1px 3px 5px black"/>

#### What your error log looks like after using `v.takeover()`
<img src="https://gitlab.com/QuintenJustus/vividlog/raw/master/assets/errorcatching.png"
     alt="Vivid Log" style="border-radius:5px; box-shadow: 1px 3px 5px black"/>

## Release History (v1.5.0)
* 1.5.0
    * Added new method called `v.style()` in which you can define your own log style
    * A lot of refactoring of the code, less chaos more nice code
* 1.3.15
    * `v.takeover()` renamed to `v.takeOver()`
    * New sample images
    * Readme fixes and updates
* 1.3.0 
    * Added support to log multiple variables
    * Added ability to group variables 
* 1.0.0
    * The first release, it's now working and can be used.
* 0.9.0
    * Added the actual code; v.err() / v.debug() / v.log() / v.done() / v.warn() / v.info() / v.say()
    * Added option to configure some settings
    * Added semi-support for FireFox
* 0.0.2
    * Work in progress

## Tested on Chrome / Firefox / Opera
> If anyone could share some experiences with other browsers with me I would be very thankful!

## Meta

Distributed under the MIT license. See ``LICENSE`` for more information.

> [gitlab.com/QuintenJustus](https://gitlab.com/QuintenJustus)
