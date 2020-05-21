---
layout: inner
title: About
permalink: /about/
---
{% if site.enable_contact == true %}
{% include contact-modal.html %}
{% endif %}

<div class="in-progress-container">
    <div class="in-progress-header">
    <div class="in-progress-i">
        <i class="fa fa-exclamation-circle fa-lg"></i>
    </div>
    <div>
        <h3>Sorry, I'm still working on this part of the site.</h3>
    </div>
    </div>
    <div>
        <p>
            In the meantime, feel free to <a data-toggle="modal" data-target="#contact" class="modal-link modal-link-color">get in touch</a>.
        </p>
    </div>
</div>