"github.io 블로그 첫 글"
======================

#"github.io 블로그 첫 글 작성해봅니다."
---------------------------------

-Blog
[Blog](https://codms0201.github.io)
<header class="header-page">
  <h1 class="page-title">{{page.title}}</h1>
  {% if page.last_modified_at %}
    <div class="page-date"><span>{{page.last_modified_at | date: '%Y, %b %d'}}&nbsp;&nbsp;&nbsp;&nbsp;</span></div>
  <lastmod> tag
The <lastmod> tag in the sitemap.xml will reflect by priority:

1. The modified date of the file as reported by the filesystem if you have jekyll-last-modified-at plugin installed (not compatible with GitHub Pages auto building)
2. A personalised date if you add the variable last_modified_at: with a date in the Front Matter
3. The creation date of your post (corresponding to the post.date variable)
