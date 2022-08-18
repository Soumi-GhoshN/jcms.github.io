
## The JCMS events

The choice of the speakers is still in progress.
<br>
We would like to hear about your interests: if you have a speaker to suggest, let us know by sending an email to the [organising team](../#contacts)!

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


