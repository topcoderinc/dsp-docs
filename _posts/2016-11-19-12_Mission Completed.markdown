---
layout: post
title:  "12_Mission Completed"
date:   2016-11-19 19:41:45 +0700
categories: post
---

<img src="{{ site.github.url }}/images/posts/2016-11-19/12_Mission-Completed.jpg">

### Component Structure

{% highlight js %}
App
│───Header
└───Content
│   └───Breadcrumb
│   └───MissionProgressHeader
│   └───MissionProgress
│   │   └───MissionProgressDetail
│   │   └───MissionProgressContact
│   │   └───MissionProgressDroneDetails
│   │   └───MissionProgressDroneEstimation
│   │   └───StatusDetailMapRoute
│   │   │   └───DroneRoutes
│   │   │   └───DroneLocations
│   │   └───StatusDetailFrontCamera
│   │   └───StatusDetailBackCamera
│   └───MissionGallery
│       └───MissionGalleryItem
└───Footer
{% endhighlight %}

### Recommended Libraries

* [Map](https://github.com/istarkov/google-map-react)
* [Slideshow](https://github.com/xiaolin/react-image-gallery)

### PropTypes

{% highlight ruby %}

-- MissionProgressDetail.jsx --
MissionProgressDetail.propTypes = {
  type: PropTypes.string.isRequired,
  delivereditem: PropTypes.string.isRequired,
  weight: PropTypes.number.isRequired,
  deliverytime: PropTypes.date.isRequired,
  pickuplocation: PropTypes.string.isRequired,
  dropofflocation: PropTypes.string.isRequired,
  distance: PropTypes.number.isRequired,
  payout: PropTypes.number.isRequired,
};

-- MissionProgressContact.jsx --
MissionProgressContact.propTypes = {
  name: PropTypes.string.isRequired,
  address: PropTypes.string.isRequired,
  phone: PropTypes.number.isRequired,
  email: PropTypes.string.isRequired,
};

-- MissionProgressDroneDetails.jsx --
MissionProgressDroneDetails.propTypes = {
  serial: PropTypes.serial.isRequired,
  name: PropTypes.string.isRequired,
  type: PropTypes.string.isRequired,
  launch: PropTypes.date.isRequired,
  estimatedarrival: PropTypes.date.isRequired,
  speed: PropTypes.number.isRequired,
};

-- MissionProgressDroneEstimation.jsx --
MissionProgressDroneEstimation.propTypes = {
  timeoflaunch: PropTypes.string.isRequired,
  speed: PropTypes.number.isRequired,
  distance: PropTypes.number.isRequired,
  time: PropTypes.string.isRequired,
};

-- RequestMap.jsx --
RequestMap.propTypes = {
  routes: PropTypes.string.isRequired,
  eta: PropTypes.string.isRequired,
};

-- MissionGalleryItem.jsx --
MissionGalleryItem.propTypes = {
  photo: PropTypes.string.isRequired,
};

{% endhighlight %}
