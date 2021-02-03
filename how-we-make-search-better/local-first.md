# Local First

We will offer browser extensions which individuals can optionally install. These extensions will retain \(if desired\) local query data and also sync data down from our servers that can expedite queries.

One of the salient examples of how this could expedite searches is by using past search queries. We can cache the results of past searches on your local computer and when you make the same query again return the results without unnecessary network traffic. In addition, we can provide a regular checking mechanism that updates the cached results with the latest results on a regular basis to ensure your local results are not inferior to those on our servers.

{% hint style="info" %}
Thankfully most major browsers are now onboard with the [WebExtensions API](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions) so our job will be much easier than those who have previously written fully custom extensions for each browser.
{% endhint %}

In addition, these extensions will \(optionally\) provide advanced bookmarking, highlighting, annotation, and save for later functionality.

{% hint style="info" %}
Some good products in this space currently include [Pocket](https://getpocket.com/) and [Diigo](https://diigo.com/). Another highly interesting option is [Memex](https://getmemex.com/).
{% endhint %}

If users are willing to share some or all of this data with us we believe it will help us improve our search results.

All extensions would have a strong emphasis on ensuring the security of user data and of using the minimum permissions possible to run.

{% hint style="info" %}
It is crazy the permissions many \(popular!\) extensions are requesting of users. These permissions go far beyond the scope of what is required to perform their functionality. It often includes permission to monitor everything you do, including on sensitive sites \(e.g. banking\). We will be clear on exactly what permissions we are using and why!
{% endhint %}

