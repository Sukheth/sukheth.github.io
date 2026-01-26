---
layout: page
title: Home
id: home
permalink: /
---

### About Me

I'm Sukheth, presently an associate at the Boston Consulting Group. I live in Bangalore and have spent most of my life here; except for study in Chennai & brief stays in Noida, London, New Castle, Navi Mumbai and Pune in that order. 

Here's what I've been up-to [[Previously]]

### Elsewhere

- Twitter: [@sukhethk](https://twitter.com/sukhethk)
- Instagram [@sukheth.k](https://instagaram.com/sukheth.k)
- LinkedIn: [Sukheth Kallupalli](https://linkedin.com/sukheth)
- Email: [sukheth.kallupalli@gmail.com](mailto:sukheth.kallupalli@gmail.com)
- BeReal: [@sukheth](bere.al/sukheth)

We can have coffee - [cal.com/sukheth](https://cal.com/sukheth)

<strong>Recently updated notes</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 5 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
