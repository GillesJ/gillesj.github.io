---
layout: page
title: About me
redirect_from:
  - "/about/"
  - "/info/"
---

Hi, I'm Gilles Jacobs, your go-to expert in navigating the complex world of Natural Language Processing, Machine Learning, Data Science, and AI. Armed with a Ph.D. in NLP and a profound passion for the intricacies of language and technology, I delve into automating complex processes and extracting valuable insights from both unstructured text and structured data. Over the past eight years, my experience has spanned from academic research to shaping commercial products, always with a keen eye on the practical application of cutting-edge tech. Here, I share insights and experiences from my professional journey, or whatever grabs my (self-)attention 🤓.

## Contact
You can message me by using the email form below:

<form action="https://formspree.io/mzbzzggb" method="POST">
  <label>
    Your email:
    <input type="text" name="_replyto">
  </label>
  <br>
  <label>
    Your message:
    <textarea name="message"></textarea>
  </label>
  <button type="submit">Send</button>
</form>

If you need more secure and confidential communication you can find [my PGP public encryption key on keybase](https://keybase.io/gillesjacobs).

## Find me on:
<ul class="social-links">
  {% for social_link in site.aboutme-social-links %}
    {% if social_link[1] != "" %}
      <li><a href="{{ social_link[1] }}" title="{{ social_link[0] }}">
        {{ social_link[0] }}
      </a></li>
    {% endif %}
  {% endfor %}
</ul>
