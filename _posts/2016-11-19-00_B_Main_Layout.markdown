---
layout: post
title:  "00_B_Main_Layout"
date:   2016-11-19 19:41:45 +0700 19:41:45 +0700
categories: post
---

<img src="{{ site.github.url }}/images/posts/2016-11-19/Main_Layout.jpg">

### Component Structure

{% highlight js %}
App
│───Header
│   └───Logo
│   └───GeoLocation
│   └───Search
│   └───CategoryDropdown
│   └───SignUp
│   └───Login
└───Content
│   └───**Check Related Pages**
└───Footer
    └───Copyright
    └───FooterLinks
{% endhighlight %}

### Recommended Libraries

* N/A

### PropTypes

{% highlight ruby %}
-- Header.jsx --
Header.propTypes = {
  location: PropTypes.string.isRequired,
  selectedCategory: PropTypes.string.isRequired,
  categories: PropTypes.array.isRequired,
  notifications: PropTypes.array.isRequired,
  user: PropTypes.object.isRequired,
};

{% endhighlight %}
