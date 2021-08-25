---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

  <div class="vedanta-header p-3 pb-md-4 mx-auto text-center">
    <h1 class="display-4 fw-normal">syllabus</h1>
  </div>


The [essentials syllabus]({{site.baseurl}}/) is nothing more than the basic introduction to each shastra.
The traditional syllabus is far more rigorous and comprehensive.
The full vedanta syllabus for the famed Tenali exams and Nagara pariksha are given below.

<div class="card-group">
    {% for syllabus in site.cards_syllabus %}
      <div class="card rounded-3">
          <div class="card-header py-3 text-center">
              <h4 class="my-0 fw-normal">{{ syllabus.title }}</h4>
          </div>
          <div class="card-body">
              <div class="p-3">
                  {{ syllabus.content }}
              </div>
          </div>
      </div>
    {% endfor %}
</div>

