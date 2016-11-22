---
layout: post
title:  "11_Mission_Progress"
date:   2016-11-19 19:41:45 +0700
categories: post
---

<img src="{{ site.github.url }}/images/posts/2016-11-19/11_Mission_Progress.jpg">

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
└───Footer
{% endhighlight %}

### Recommended Libraries

* [ProviderMap](https://github.com/istarkov/google-map-react)
