---
layout: post
title:  "02_Browse_Provider2(Map_View_Quick_Summary_Drone)"
date:   2016-11-19 19:41:45 +0700
categories: post
---

<img src="{{ site.github.url }}/images/posts/2016-11-19/02_Browse_Provider2(Map_View_Quick_Summary_Drone).jpg">

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
│       │   └───DronesTooltips
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

-- ProviderMap.jsx --
ProviderMap.propTypes = {
  droneslocations: PropTypes.array.isRequired,
  userlocation: PropTypes.string.isRequired,
  dronetooltips: PropTypes.array.isRequired,
};

-- DronesTooltips.jsx --
DronesTooltips.propTypes = {
  title: PropTypes.string.isRequired,
  rating: PropTypes.string.isRequired,
  status: PropTypes.string.isRequired,
  distance: PropTypes.number.isRequired,
  ratepermile: PropTypes.number.isRequired,
};

{% endhighlight %}
