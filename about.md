---
title: About Us
description: Here's what we're all about.
layout: default
---

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
                    <span><i class="fas fa-graduation-cap"></i> {{ contributor.degree }}</span>
                </div>
                <div>
                    <span><i class="fab fa-github"></i> {{ contributor.github }}</span>
                </div>
                
            </li>
        </div>
    </a>
    {% endfor %}
</ul>

### Who are we?

Scrap & Trace is a project made for our third year group project by a group of students from Heriot-Watt University in Edinburgh, Scotland. We are a group of students from a variety of backgrounds, including Computer Science, Computer Systems, and Software Engineering.

## The Project

This is a placeholder for the project description.
