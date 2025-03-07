---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Home
---

<div class="home">
    <h2 class="post-list-heading">Posts</h2>
    <ul class="post-list">
        {% for post in site.posts %}
        <li>
            <span class="post-meta">{{ post.date | date: "%b %d, %Y" }}</span>
            <h3>
                <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">
                    {{ post.title }}
                </a>
            </h3>
        </li>
        {% endfor %}
    </ul>
</div>
