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
│       └───MapActionButtons
└───Footer
{% endhighlight %}

### Recommended Libraries

* [Map](https://github.com/istarkov/google-map-react)
* [Tooltips1](https://github.com/react-component/tooltip)
* [Tooltips2](https://github.com/react-component/tooltip)

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

-- ProvidersGridTooltips.jsx --
ProvidersGridTooltips.propTypes = {
  status: PropTypes.string.isRequired,
  distance: PropTypes.number.isRequired,
  ratepermile: PropTypes.number.isRequired,
};

-- NotificationRow.jsx --
NotificationRow.propTypes = {
  icon: PropTypes.string.isRequired,
  title: PropTypes.string.isRequired,
  link: PropTypes.string.isRequired,
  status: PropTypes.string.isRequired,
  time: PropTypes.string.isRequired,
};

ProviderMap.propTypes = {
  droneslocations: PropTypes.array.isRequired,
  userlocation: PropTypes.string.isRequired,
  dronetooltips: PropTypes.array.isRequired,
};

{% endhighlight %}
