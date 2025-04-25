---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Danqi Chen's Publications</title>
    <!-- 自定义样式示例 -->
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            max-width: 800px;
            margin: 20px auto;
            padding: 0 20px;
        }
        a {
            color: #0066cc;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <h1>Publications</h1>
    
    <section>
        <h2>Danqi Chen's Papers</h2>
        <p>
            ➡️ Full list available at: 
            <a href="https://www.cs.princeton.edu/~danqic/papers.html" target="_blank" rel="noopener noreferrer">
                Princeton CS Page
            </a>
        </p>
    </section>

    <!-- 你可以在这里添加更多内容 -->
    <div class="custom-content">
        <h3>Selected Publications</h3>
        <ul>
            <li>[示例] Add your selected papers here</li>
        </ul>
    </div>

</body>
</html>


{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
