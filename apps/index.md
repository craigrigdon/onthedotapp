---
layout: default
title: Apps
description: Privacy and support pages for apps besides On The Dot, hosted on onthedotapp.com.
permalink: /apps/
---

<section class="wrap band apps-list">
  <p class="lede">Other apps by this developer.</p>
  <div class="cards">
    <a class="card card-app" href="{{ "/" | relative_url }}">
      {% include app-icon.html name="onthedot" class="app-icon app-icon-sm" alt="" size="128" %}
      <div>
        <h3>On The Dot</h3>
        <p>Leave-time alerts from where you are. Privacy and support live at the root of this site.</p>
      </div>
    </a>
    <a class="card card-app" href="{{ "/apps/stillbroke/" | relative_url }}">
      {% include app-icon.html name="stillbroke" class="app-icon app-icon-sm" alt="" size="128" %}
      <div>
        <h3>Still Broke</h3>
        <p>Solo use is free. Invite family with optional Household unlock. Your numbers stay in iCloud.</p>
      </div>
    </a>
  </div>
</section>
