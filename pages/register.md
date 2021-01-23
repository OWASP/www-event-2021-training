---

title: Event Registration
layout: event_noheader
permalink: /register/

---

### Registration 
{% if site.data.event-details.registration_open %}

{% else %}
<br>
# Registration is closed.
<br>
{% endif %}

{% if site.data.event-details.registration_open %}
### REGISTRATION IS NOW CLOSED.
 
{% include registration_form.md show_dietary_restrictions="false" primary_color="#0079a7" %}

Also, **[check out our sponsors for a chance to win some cool prizes](/sponsors/swag/)**
{% endif %}


Questions? [events@owasp.com](mailto:events@owasp.com?subject=Training%20Event%20Inquiry)
