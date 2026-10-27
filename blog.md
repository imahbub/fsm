---
title: প্রকাশনা সমূহ
nav_order: -6
---

# বিগত সময়ে প্রকাশিত লেখাসমূহ:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

আপনার লেখাও জমা দিন। এই রিপোটি ফর্ক করে _posts ফোল্ডারে YYYY-MM-DD-Title-optional.md ফাইলটি যোগ করুন। 

‍‍‍‍‍‍~~~markdown
---
layout: post
title: আপনার লেখার শিরোনাম
---

আপনার লেখা এখানে।
‍‍‍~~~

Then `git add * && git commit -m "একটি কমিট বার্তা" && git push -u origin branch`

