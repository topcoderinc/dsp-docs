---
layout: post
title:  "02_Browse_Provider3(List_View_Quick_Summary Drone)"
date:   2016-11-19 19:41:45 +0700
categories: post
---

<img src="{{ site.github.url }}/images/posts/2016-11-19/02_Browse_Provider3(List_View_Quick_Summary_Drone).jpg">

### Component Structure

{% highlight js %}
App
│───Header
└───Content
│   └───BrowseProvider
│   │   └───BrowseProviderHeader
│   │   │   └───BrowseProviderSearch
│   │   │   └───BrowseProviderFilter
│   │   │   └───BrowseProviderSort
│   │   └───ProvidersGrid
│   │   │   └───ProvidersGridItem
│   │   │   │   └───ProvidersGridTooltips
│   └───ProviderMap
│       └───UserLocation
│       └───DroneLocation
│       │   └───DronesTooltips
│       └───MapActionButtons
└───Footer
{% endhighlight %}

### Recommended Libraries

* [ProviderMap](https://github.com/istarkov/google-map-react)
* [Tooltips1](https://github.com/react-component/tooltip)
* [Tooltips2](https://github.com/react-component/tooltip)
