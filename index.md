---
layout: default
title: ""
---

<section class="hero">
    <h1>Willkommen beim KC Standard Lüttich!</h1>
    <p>Wir sind ein Kegelverein bestehend aus 18 Mitgliedern und wurden 2020 gegründet.</p>
</section>

<section class="about">
    <h2>Über Uns</h2>
    <p>Der KC Standard Lüttich ist ein engagierter und leidenschaftlicher Kegelverein, der sich auf Sport und Gemeinschaft fokussiert. Unsere Mitglieder kommen regelmäßig zusammen, um sich sportlich zu betätigen und Spaß zu haben.</p>
</section>

<section class="blog-posts">
    <h2>Neueste Beiträge</h2>
    <ul>
        {% for post in site.posts %}
        <li>
            <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%d.%m.%Y" }}
        </li>
        {% endfor %}
    </ul>
</section>
