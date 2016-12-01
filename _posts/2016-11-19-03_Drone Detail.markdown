---
layout: post
title:  "03_Drone_Detail"
date:   2016-11-19 19:41:45 +0700
categories: post
---

<img src="{{ site.github.url }}/images/posts/2016-11-19/03_Drone_Detail.jpg">

### Component Structure

{% highlight js %}
App
│───Header
└───Content
│   └───Breadcrumb
│   └───DroneDetailBanner
│   └───DroneAbout
│   └───DroneSpecification
│   └───Services
│   │   └───ServicesItem
│   └───Feedback
│       └───FeedbackHeader
│       └───FeedbackItem
│           └───FeedbackItemButton
└───Footer
{% endhighlight %}

### Recommended Libraries

* N/A

### PropTypes

{% highlight ruby %}

-- DroneDetailBanner.jsx --
DroneDetailBanner.propTypes = {
  photo: PropTypes.string.isRequired,
  title: PropTypes.string.isRequired,
  badge: PropTypes.bool.isRequired,
  rating: PropTypes.number.isRequired,
  availabledrones: PropTypes.number.isRequired,
  totaldrones: PropTypes.number.isRequired,
  insurance: PropTypes.number.isRequired,
  hourlyrate: PropTypes.number.isRequired,
  completedjob: PropTypes.number.isRequired,
};

-- DroneAbout.jsx --
DroneAbout.propTypes = {
  photo: PropTypes.string.isRequired,
  title: PropTypes.string.isRequired,
  description: PropTypes.string.isRequired,
};

-- DroneSpecification.jsx --
DroneSpecification.propTypes = {
  dronephotos: PropTypes.array.isRequired,
  dronespecification: PropTypes.array.isRequired,
  dronesbenefits: PropTypes.array.isRequired,
};

-- ServicesItem.jsx --
ServicesItem.propTypes = {
  photo: PropTypes.string.isRequired,
  icon: PropTypes.string.isRequired,
  title: PropTypes.string.isRequired,
};

-- FeedbackItem.jsx --
FeedbackItem.propTypes = {
  photo: PropTypes.string.isRequired,
  time: PropTypes.string.isRequired,
  description: PropTypes.string.isRequired,
  rating: PropTypes.number.isRequired,
};

{% endhighlight %}
