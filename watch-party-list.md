---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: List of all ICSE 2021 Watch Parties
---

Add yours by copying & filling out the [template](watch-party-details/template-city-organization.md)!

<ul>
  {% for announcement in site.watch_party_announcements %}
    <li>
      <a href="{{ announcement.url }}">{{ announcement.title }}</a>
      <p>Open for registrations: {{announcement.open_for_registrations}}<br>
      Continent: {{announcement.continent}}<br>
      Country: {{announcement.country}}<br>
      City: {{announcement.city}}</p>
      <!-- <h3>{{ author.position }}</h3>
      <p>{{ author.content | markdownify }}</p> -->
    </li>
  {% endfor %}
</ul>


## Africa

## Asia

## Europe

## North-America

## South-America
