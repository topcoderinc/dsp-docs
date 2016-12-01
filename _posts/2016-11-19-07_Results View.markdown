---
layout: post
title:  "07_Results_View"
date:   2016-11-19 19:41:45 +0700
categories: post
---

<img src="{{ site.github.url }}/images/posts/2016-11-19/07_Results_View.jpg">

### Component Structure

{% highlight js %}
App
│───Header
└───Content
│   └───Breadcrumb
│   └───StatusDetail
│   │   └───StatusDetailHeader
│   │   └───StatusDetailInfo
│   │   │   └───StatusProjectInfo
│   │   │   └───StatusDetailMapRoute
│   │   └───DeployMissionParameters
│   │   │   └───OverallDronePerformance
│   │   │   └───DroneGraphPerformance
│   │   └───MissionGallery
│   │   │   └───MissionGalleryItem
│   │   │   └───MissionGalleryPagination
└───Footer
{% endhighlight %}

### Recommended Libraries

* [Map](https://github.com/istarkov/google-map-react)
* [Slideshow](https://github.com/xiaolin/react-image-gallery)

### PropTypes

{% highlight ruby %}

-- StatusDetailInfo.jsx --
StatusDetailInfo.propTypes = {
  name: PropTypes.string.isRequired,
  description: PropTypes.string.isRequired,
  address: PropTypes.string.isRequired,
  contactname: PropTypes.string.isRequired,
  telephone: PropTypes.string.isRequired,
};

-- StatusDetailMapRoute.jsx --
StatusDetailMapRoute.propTypes = {
  routes: PropTypes.string.isRequired,
  dronelocation: PropTypes.string.isRequired,
};

-- OverallDronePerformance.jsx --
OverallDronePerformance.propTypes = {
  speed: PropTypes.number.isRequired,
  easeofuse: PropTypes.number.isRequired,
  flightperformance: PropTypes.number.isRequired,
  cameraperformance: PropTypes.number.isRequired,
};

-- DroneGraphPerformance.jsx --
DroneGraphPerformance.propTypes = {
  time: PropTypes.string.isRequired,
  altitude: PropTypes.number.isRequired,
};

-- MissionGalleryItem.jsx --
MissionGalleryItem.propTypes = {
  photo: PropTypes.string.isRequired,
};

{% endhighlight %}
