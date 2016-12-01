---
layout: post
title:  "02_Browse_Provider"
date:   2016-11-19 19:41:45 +0700
categories: post
---

<img src="{{ site.github.url }}/images/posts/2016-11-19/02_Browse_Provider.jpg">

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

-- ProvidersGridItem.jsx --
ProvidersGridItem.propTypes = {
  sponsored: PropTypes.string.isRequired,
  title: PropTypes.string.isRequired,
  tooltips: PropTypes.string.isRequired,
  badge: PropTypes.bool.isRequired,
  completedjob: PropTypes.array.isRequired,
  rating: PropTypes.number.isRequired,
};

-- ProviderMap.jsx --
ProviderMap.propTypes = {
  droneslocations: PropTypes.array.isRequired,
  userlocation: PropTypes.string.isRequired,
};

{% endhighlight %}
