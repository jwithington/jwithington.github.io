---
layout: page
title: Say Hello
permalink: /contact/
---

Hit me up at jwithington [at] gmail. 

Although, I don't check that often. Try [@jwithy][tweet] instead.

[tweet]: https://twitter.com/jwithy

<!-- <div class="py2">
  {% if site.ajaxify_contact_form %}
    <form class="form-stacked">
      <input type="text" name="email" class="field-light" placeholder="Email Address">
      <textarea type="text" name="content" class="field-light" rows="5" placeholder="What would you like to say?"></textarea>
      <input type="hidden" name="_subject" value="New submission!" />
      <input type="text" name="_gotcha" style="display:none" />
      <button type='submit' class="button button-blue button-big mobile-block">Say Hello</button>
    </form>
  {% else %}
    <form action="https://formspree.io/{{ site.email }}" method="POST" class="form-stacked">
      <input type="text" name="email" class="field-light" placeholder="Email Address">
      <textarea type="text" name="content" class="field-light" rows="5" placeholder="What would you like to say?"></textarea>
      <input type="hidden" name="_next" value="{{ site.baseurl }}/thanks/" />
      <input type="hidden" name="_subject" value="New submission!" />
      <input type="text" name="_gotcha" style="display:none" />
      <input type="submit" class="button button-blue button-big mobile-block" value="Say Hello">
    </form>
  {% endif %}
</div>

{% if site.ajaxify_contact_form %}
  {% include ajaxify_content_form.html %}
{% endif %} -->
