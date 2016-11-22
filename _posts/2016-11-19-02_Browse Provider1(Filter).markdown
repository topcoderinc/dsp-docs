---
layout: post
title:  "02_Browse_Provider1(Filter)"
date:   2016-11-19 19:41:45 +0700
categories: post
---

<img src="{{ site.github.url }}/images/posts/2016-11-19/02_Browse_Provider1(Filter).jpg">

### Component Structure

{% highlight js %}
App
│───Header
│   └───Notification
│   │   └───NotificationRow
└───Content
│   └───Filter
│   │   └───BrowseProviderHeader
│   │   │   └───BrowseProviderFilter
│   │   └───ProvidersFilter
│   │   │   └───ProvidersGridForm
│   └───ProviderMap
│       └───UserLocation
│       └───DroneLocation
│       └───MapActionButtons
└───Footer
{% endhighlight %}

### Recommended Libraries

* [ProviderMap](https://github.com/istarkov/google-map-react)
* [Dropdown](https://github.com/JedWatson/react-select)
* [RangeSlider](https://github.com/react-component/slider)
* [RadioButton & Checkboxes](http://www.luqin.xyz/react-icheck/#/?_k=ncq8ed)
