---
layout: default
---


<article>
  <h2 class="post-title">{{ page.title }}</h2>
  <p><small>{{ page.date | date: "%B %d, %Y" }}</small></p>
  {{ content }}
  <!-- Giscus comments section -->
  <div id="giscus_thread"></div>
  <script src="https://giscus.app/client.js"
        data-repo="amin7tsix/blog"
        data-repo-id="R_kgDOOxW9mQ"
        data-category="General"
        data-category-id="DIC_kwDOOxW9mc4CqziA"
        data-mapping="pathname"
        data-strict="0"
        data-reactions-enabled="1"
        data-emit-metadata="0"
        data-input-position="top"
        data-theme="preferred_color_scheme"
        data-lang="fa"
        crossorigin="anonymous"
        async>
  </script>
</article>
