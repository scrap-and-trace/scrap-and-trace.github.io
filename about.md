---
title: About Us
layout: default
---

We're Scrap and Trace, and for the time being, this is some placeholder text.

## The Team

<ul class="about-list">
    {% for contributor in site.data.contributors %}
    <a href="{{ contributor.html_url }}">
        <div class="about-container" href="{{ contributor.html_url }}">
            <li>
                <img src="{{ contributor.avatar_url }}" alt="{{ contributor.login }}" class="avatar">
                <div>
                    <b>{{ contributor.name }}</b>
                </div>
                <div>
                    {{ contributor.role }}
                </div>
                <div>
                    <span><i class="fab fa-github"></i> {{ contributor.github }}</span>
                </div>
            </li>
        </div>
    </a>
    {% endfor %}
</ul>

## The Project

This is a placeholder for the project description.
