---
layout: home
---

<div class="index-content learn">
    <div class="section">
        <ul class="artical-cate">
            <li class="on"><a href="/"><span>学习笔记</span></a></li>
            <li style="text-align:center"><a href="/fiction"><span>独创小说</span></a></li>
            <li style="text-align:right"><a href="/share"><span>各种分享</span></a></li>
        </ul>

        <div class="cate-bar"><span id="cateBar"></span></div>

        <ul class="artical-list">
        {% for post in site.categories.learn %}
            <li>
                <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
                <div class="title-desc">{{ post.description }}</div>
            </li>
        {% endfor %}
        </ul>
    </div>
    <div class="aside">
    </div>
</div>
