---
date: "2022-09-03T16:26:51-07:00"
title: Tips-n-Tricks
---

# For the Fellow Blogger:

* Create catchy blog titles by using [seopressor.com/blog-title-generator](https://seopressor.com/blog-title-generator).  Although you may not use the titles, they may help you focus on a central theme for a post which may be appealing for a wider audience.

* A simple code template to split a longer blog into multiple pages was obatined from [this blogtimenow.com post](https://blogtimenow.com/blogging/splitting-long-blog-post-blogger/).  I then added 'scrollTo' to each navigation so that the window appears at the top of the context instead of at the bottom. Example:

```
<script style="text/javascript">
jQuery(document).ready(function(){
jQuery('.page1').click(function(){
jQuery('.content_intro').show();
jQuery('.content1').hide();
...
jQuery('.window').scrollTo(0,0);
return false;
});
```
