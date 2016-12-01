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

* [Map](https://github.com/istarkov/google-map-react)

### PropTypes

{% highlight ruby %}

-- DroneInfoDetails.jsx --
DroneInfoDetails.propTypes = {
  photo: PropTypes.string.isRequired,
  title: PropTypes.string.isRequired,
  description: PropTypes.string.isRequired,
};

-- DroneInfoSpecification.jsx --
DroneInfoSpecification.propTypes = {
  dronephotos: PropTypes.array.isRequired,
  dronespecification: PropTypes.array.isRequired,
  dronesbenefits: PropTypes.array.isRequired,
};

-- LastCompletedMissions.jsx --
LastCompletedMissions.propTypes = {
  route: PropTypes.string.isRequired,
  id: PropTypes.string.isRequired,
  type: PropTypes.string.isRequired,
  date: PropTypes.string.isRequired,
  location: PropTypes.string.isRequired,
};

{% endhighlight %}
