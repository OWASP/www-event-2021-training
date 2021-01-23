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
### **All courses take place simultaneously on January 26-27 from 12:00-4:00pm EST. Please only register for one course. Please note any application steps which may be required to attend select courses below.**
 
{% include registration_form.md show_dietary_restrictions="false" primary_color="#0079a7" %}

Also, **[check out our sponsors for a chance to win some cool prizes](/sponsors/swag/)**
{% endif %}


Questions? [events@owasp.com](mailto:events@owasp.com?subject=Training%20Event%20Inquiry)
