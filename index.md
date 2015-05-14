---
layout: home
title: d08ble Home
---
### [LiveComment 2.10 - Node.js library for code comments](https://github.com/d08ble/livecomment)
<br>
LiveComment is very simple:

#### Live comment usage sample:

{% highlight javascript %}
// File: app.jsx

// My code block - import section [

import async from "async";
import React from "react";
import Router from "react-router";

// My code block - import section ]
{% endhighlight %}

#### Install

{% highlight javascript %}
npm install livecomment --save
{% endhighlight %}

#### Configure paths

{% highlight javascript %}
var LiveComment = require('../livecomment')

var options = {
    debug: 1,
    common: {
      ignore: [
        '.git',
      ]
    },
    paths: ['/path/to/file', ...]
}

var livecomment = new LiveComment(options)
{% endhighlight %}

#### Run node.js

{% highlight javascript %}
$ node_modules/livecomment/bin/livecomment
{% endhighlight %}

#### View in browser
{% highlight javascript %}
open http://localhost:3070/
{% endhighlight %}

