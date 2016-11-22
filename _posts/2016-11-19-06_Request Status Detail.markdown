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
│   └───StatusDetailHeader
│   └───StatusDetail
│   │   └───StatusDetailInfo
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
