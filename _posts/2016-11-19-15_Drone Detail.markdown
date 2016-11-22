---
layout: post
title:  "15_Drone_Detail"
date:   2016-11-19 19:41:45 +0700
categories: post
---

<img src="{{ site.github.url }}/images/posts/2016-11-19/15_Drone_Detail.jpg">

### Component Structure

{% highlight js %}
App
│───Header
└───Content
│   └───Breadcrumb
│   └───DroneDetails
│       └───DroneDetailsHeader
│       └───DroneDetailsTabs
│           └───DroneInfo
│           │   └───DroneInfoDetails
│           │   └───DroneInfoSpecification
│           │   └───LastCompletedMissions
│           │   │   └───LastCompletedMissionsItem
│           └───DroneSchedule
└───Footer
{% endhighlight %}

### Recommended Libraries

* [ProviderMap](https://github.com/istarkov/google-map-react)
