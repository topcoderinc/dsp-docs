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
│   └───StatusDetailHeader
│   └───StatusDetail
│   │   └───StatusDetailInfo
│   │   └───StatusDetailMapRoute
│   └───DeployMissionParameters
│   └───DroneGraphPerformance
│   └───MissionGallery
│   │   └───MissionGalleryItem
│   │   └───MissionGalleryPagination
└───Footer
{% endhighlight %}

### Recommended Libraries

* [ProviderMap](https://github.com/istarkov/google-map-react)
