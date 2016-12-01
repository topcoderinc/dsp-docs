---
layout: post
title:  "02_Browse_Provider0"
date:   2016-11-19 19:41:45 +0700
categories: post
---

<img src="{{ site.github.url }}/images/posts/2016-11-19/02_Browse_Provider0.jpg">

### Component Structure

{% highlight js %}
App
│───Header
│   └───Notification
│   │   └───NotificationRow
└───Content
│   └───BrowseProvider
│   │   └───BrowseProviderHeader
│   │   │   └───BrowseProviderSearch
│   │   │   └───BrowseProviderFilter
│   │   │   └───BrowseProviderSort
│   │   └───ProvidersGrid
│   │   │   └───ProvidersGridItem
│   └───ProviderMap
│       └───UserLocation
│       └───DroneLocation
│       └───MapActionButtons
└───Footer
{% endhighlight %}

### Recommended Libraries

* [Map](https://github.com/istarkov/google-map-react)

### PropTypes

{% highlight ruby %}

-- ProviderMap.jsx --
ProviderMap.propTypes = {
  droneslocations: PropTypes.array.isRequired,
  userlocation: PropTypes.string.isRequired,
};

{% endhighlight %}
