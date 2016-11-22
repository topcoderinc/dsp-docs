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

* [ProviderMap](https://github.com/istarkov/google-map-react)
* [PopularDrones](https://github.com/xiaolin/react-image-gallery)
