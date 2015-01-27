---
layout: page
tagline: 人丑就该多读书.
---

{% for post in site.posts %}

{{ post.date | date_to_string}} 
» 
**[{{ post.title }}]({{ post.url }})** 
&nbsp; 
{{post.description}}

{% endfor %}

---

- [about](http://about.me/dinghim)
- [github](http://github.com/dinghim)
- [douban](http://www.douban.com/people/uglyfly/)
- [weibo](http://weibo.com/uglyfly/)
