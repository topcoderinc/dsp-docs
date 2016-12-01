---
layout: post
title:  "06_Request_Status_Detail"
date:   2016-11-19 19:41:45 +0700
categories: post
---

<img src="{{ site.github.url }}/images/posts/2016-11-19/06_Request_Status_Detail.jpg">

### Component Structure

{% highlight js %}
App
│───Header
└───Content
│   └───Breadcrumb
│   └───StatusDetail
│   │   └───StatusDetailHeader
│   │   └───StatusDetailInfo
│   │   └───StatusDetailMap
│   │   │   └───StatusDetailMapRoute
│   │   │   │   └───DroneRoutes
│   │   │   │   └───DroneLocationsLegends
│   │   │   │   └───DroneLocationsETA
│   │   │   └───StatusDetailFrontCamera
│   │   │   └───StatusDetailBackCamera
│   └───MissionGallery
└───Footer
{% endhighlight %}

### Recommended Libraries

* [Map](https://github.com/istarkov/google-map-react)

### PropTypes

{% highlight ruby %}

-- StatusDetailInfo.jsx --
StatusDetailInfo.propTypes = {
  timeoflaunch: PropTypes.date.isRequired,
  timecompleted: PropTypes.date.isRequired,
  speed: PropTypes.number.isRequired,
  distance: PropTypes.number.isRequired,
  name: PropTypes.string.isRequired,
};

-- StatusDetailMapRoute.jsx --
StatusDetailMapRoute.propTypes = {
  routes: PropTypes.string.isRequired,
  dronelocation: PropTypes.string.isRequired,
  eta: PropTypes.string.isRequired,
};

{% endhighlight %}
