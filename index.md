# Welcome to Yeti 'Nother Paper
With a bit of luck, we'll be publishing a summary of a bioengineering (broadly construed) paper which has caught our eye once a month.

<ul class="posts">
    {% for post in site.posts %}
        <li>
            <span>{{ post.date | date_to_string }}</span>
            &raquo;
            <a href="{{ post.url }}">{{ post.title }}</a>
        </li>
    {% endfor %}
</ul>
