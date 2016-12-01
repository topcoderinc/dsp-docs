---
layout: post
title:  "04_Service_Request"
date:   2016-11-19 19:41:45 +0700
categories: post
---

<img src="{{ site.github.url }}/images/posts/2016-11-19/04_Service_Request.jpg">

### Component Structure

{% highlight js %}
App
│───Header
└───Content
│   └───ServiceAddress
│   │   └───UserLocation
│   │   └───TargetLocation
│   └───ItemRequestForm
│   └───ProviderMap
│       └───DroneRoutes
│       └───DroneCurrentLocation
│       └───MapLegends
└───Footer
{% endhighlight %}

### Recommended Libraries

* [Map](https://github.com/istarkov/google-map-react)
* [Dropdown](https://github.com/JedWatson/react-select)
* [RadioButton & Checkboxes](http://www.luqin.xyz/react-icheck/#/?_k=ncq8ed)
* [Tooltips1](https://github.com/react-component/tooltip)
* [Tooltips2](https://github.com/react-component/tooltip)

### PropTypes

{% highlight ruby %}

-- ServiceAddress.jsx --
ServiceAddress.propTypes = {
  userlocation: PropTypes.string.isRequired,
  targetlocation: PropTypes.string.isRequired,
};

-- ProviderMap.jsx --
ProviderMap.propTypes = {
  routes: PropTypes.string.isRequired,
  dronelocation: PropTypes.string.isRequired,
  distance: PropTypes.number.isRequired,
};

{% endhighlight %}
