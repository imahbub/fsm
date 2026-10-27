---
title: প্রকাশনা সমূহ
nav_order: -6
---

# বিগত সময়ে প্রকাশিত লেখাসমূহ:

<ul>
  {% for post in site.posts %}
    <li>
      <h2>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      </h2>
    </li>
  {% endfor %}
</ul>

আপনার লেখাও জমা দিন। এই রিপোটি ফর্ক করে _posts ফোল্ডারে YYYY-MM-DD-Title-optional.md ফাইলটি যোগ করুন। 

```markdown
---
layout: post
title: Your post title
---

Your post
```