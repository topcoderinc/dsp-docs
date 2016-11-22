---
layout: post
title:  "04_Service_Request"
date:   2016-11-19 19:41:45 +0700
categories: post
---

<img src="{{ site.github.url }}/images/posts/2016-11-19/04_Service_Request.jpg">

### Component Structure

{% highlight js %}
App
│───Header
└───Content
│   └───Breadcrumb
│   └───ServiceRequest
│   │   └───ServiceAddress
│   │   │   └───UserLocation
│   │   │   └───TargetLocation
│   │   └───ServiceDetail
│   └───ProviderMap
│       └───DroneRoutes
│       └───DroneCurrentLocation
│       └───MapLegends
└───Footer
{% endhighlight %}

### Recommended Libraries

* [ProviderMap](https://github.com/istarkov/google-map-react)
* [Dropdown](https://github.com/JedWatson/react-select)
* [RadioButton & Checkboxes](http://www.luqin.xyz/react-icheck/#/?_k=ncq8ed)
* [Tooltips1](https://github.com/react-component/tooltip)
* [Tooltips2](https://github.com/react-component/tooltip)
