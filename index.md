---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---

[about]: (/about)

# Projects

[chimera](https://github.com/{{ site.github_username }}/chimera) Python3 interpreter in C++.

[Lua-ReQL](https://github.com/{{ site.github_username }}/Lua-ReQL) RethinkDB driver for luarocks environment.

[CaaSbootstrap](https://github.com/{{ site.github_username }}/CaaSbootstrap) microservice intended to bootstrap itself into a compiler.

[primes](https://github.com/{{ site.github_username }}/primes) Sieve of Eratosthenes implemented in golang.

[glowing-chainsaw](https://github.com/{{ site.github_username }}/glowing-chainsaw) markov chain compression algorithm to practice reversible transformations.

# Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
