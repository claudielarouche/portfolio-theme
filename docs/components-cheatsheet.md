# Components Cheat Sheet

> Quick-reference for all the `{% include %}` snippets you can use in your Markdown files.

---

## Table of Contents

1. [Alerts](#alerts)  
2. [Buttons](#buttons)  
3. [Image Gallery](#image-gallery)  
4. [Team Card](#team-card)  
5. [Testimonials](#testimonials)  

---



### Snippet

```liquid
{% raw %}
{% include alert.html
   type="warning"
   content="**Heads up!** Don’t forget to backup your site regularly." %}
{% endraw %}

Buttons

{% raw %}
{% include button.html
   url="/contact"
   text="Get in Touch"
   style="secondary" %}
{% endraw %}

Images

{% raw %}
{% include gallery.html
   images="/img/one.jpg,/img/two.jpg,/img/three.jpg"
   columns="3" %}
{% endraw %}

Team card

{% raw %}
{% include team-card.html
   photo="/img/jane-smith.jpg"
   name="Jane Smith"
   title="Lead Designer"
   bio="Jane brings 10+ years of UX experience…" %}
{% endraw %}

Testimonials

{% raw %}
{% include testimonial.html
   quote="Working with Claudie was a game-changer!"
   author="Alex Johnson"
   role="Freelance Developer"
   company="AJ Dev Co." %}
{% endraw %}
