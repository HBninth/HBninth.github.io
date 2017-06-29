<h2>Life</h2>

<ul>

  {% for post in site.categories.Life %}

    <li>

      <a href="{{ post.url }}">{{ post.title }}</a>

    </li>

  {% endfor %}

</ul>

