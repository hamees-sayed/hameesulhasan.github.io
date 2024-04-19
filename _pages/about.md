---
layout: about
title: about
permalink: /
subtitle: <a href="https://study.iitm.ac.in/ds/">DS, IIT Madras</a>

profile:
  align: right
  image: prof_pic.png
  address:

news: false  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

Hi there! I'm Hamees Ul Hasan, but you can call me Hamees. I'm currently pursuing my BS at Indian Institute of Technology (IIT) Madras, where I'm majoring in Data Science and Application. My interests lie in Statistics, Machine Learning, Data Science, Large Language Models, Deep Learning and Open Source.

Apart from academics, I enjoy playing video games, watching anime, reading comics and books on recreational mathematics and scientific humour. I'm also a sports enthusiast and enjoy playing basketball.

I played basketball for my high school team. My favourite authors include [Martin Gardner](https://www.goodreads.com/author/show/7105.Martin_Gardner) and [Randoll Munroe](https://www.goodreads.com/en/book/show/21413662).


<div class="news">
            <h2>news</h2>
            {% if site.news  -%}
            <div class="table-responsive">
              <table class="table table-sm table-borderless">
              {%- assign news = site.news | reverse -%}
              {% for item in news limit: site.news_limit %}
                <tr>
                  <th scope="row">{{ item.date | date: "%b %-d, %Y" }}</th>
                  <td>
                    {% if item.inline -%}
                      {{ item.content | remove: '<p>' | remove: '</p>' | emojify }}
                    {%- else -%}
                      <a class="news-title" href="{{ item.url | relative_url }}">{{ item.title }}</a>
                    {%- endif %}
                  </td>
                </tr>
              {%- endfor %}
              </table>
            </div>
          {%- else -%}
            <p>No news so far...</p>
          {%- endif %}
          </div>

