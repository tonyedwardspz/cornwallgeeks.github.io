---
title: Contact
layout: page
---

If it's urgent you can find other means of contacting Admins on the [Code of Conduct page](/code-of-conduct#contacting-admins). See the [Organisers page](/organisers) for more contact details.

You can email us with this form or at [{{ site.author.email }}](mailto:{{ site.author.email }}).

<form action="//formspree.io/{{ site.author.email }}"
      method="POST">
    <input type="email" name="_replyto" placeholder="{{ site.var_your_email }}">
    <input type="hidden" name="_next" value="{{ site.baseurl }}/thanks" />
    <input type="hidden" name="_subject" value="New submission from {{ site.url }}{{ site.baseurl }}" />
    <input type="text" name="_gotcha" style="display:none" />
    <textarea type="text" name="content" rows="8" placeholder="{{ site.var_your_message }}"></textarea>
    <input type="submit" value="Send">
</form>

