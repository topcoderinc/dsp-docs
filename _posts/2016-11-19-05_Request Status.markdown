---
layout: post
title:  "05_Request_Status"
date:   2016-11-19 19:41:45 +0700
categories: post
---

<img src="{{ site.github.url }}/images/posts/2016-11-19/05_Request_Status.jpg">

### Component Structure

{% highlight js %}
App
│───Header
└───Content
│   └───Breadcrumb
│   └───MyRequestStatus
│       └───MyRequestHeader
│       └───MyRequestRow
└───Footer
{% endhighlight %}

### Recommended Libraries

* N/A

### PropTypes

{% highlight ruby %}

-- MyRequestStatus.jsx --
MyRequestStatus.propTypes = {
  name: PropTypes.string.isRequired,
  provider: PropTypes.string.isRequired,
  timeoflaunch: PropTypes.date.isRequired,
  status: PropTypes.string.isRequired,
};

{% endhighlight %}
