# Welcome!

My name is Ethan Morse, and this is my blog! Here, youll find the processes that I go through 

<br>

![A professional photo](/assets/HEKLP.jpeg)

<ul>
    {% for post in site.posts %}
        <li>
            <a href="/Blog{{ post.url }}">{{ post.title }}</a>
        </li>
    {% endfor %}
</ul>