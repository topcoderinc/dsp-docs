---
layout: post
title:  "18_Service_Detail"
date:   2016-11-19 19:41:45 +0700
categories: post
---

<img src="{{ site.github.url }}/images/posts/2016-11-19/18_Service_Detail.jpg">

### Component Structure

{% highlight js %}
App
│───Header
└───Content
│   └───Breadcrumb
│   │   └───ServiceDetailHeader
│   └───ServiceDetail
│   │   └───ServiceDetailInfo
│   │   └───AvailablePackages
│   │        └───AvailablePackages
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
  description: PropTypes.string.isRequired,
};

-- AvailablePackagesItem.jsx --
AvailablePackagesItem.propTypes = {
  title: PropTypes.string.isRequired,
  icon: PropTypes.string.isRequired,
  description: PropTypes.string.isRequired,
  features: PropTypes.array.isRequired,
  pax: PropTypes.number.isRequired,
  regularprice: PropTypes.number.isRequired,
  samplelink: PropTypes.string.isRequired,
};

{% endhighlight %}
