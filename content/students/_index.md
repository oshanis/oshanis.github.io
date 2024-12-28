---
title: 'Students'
date: 2024-12-31
type: landing
summary: My Students

cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: students
    content:
      title: Students
      filters:
        folders:
          - students
    design:
      view: article-grid
      columns: 3
---

{{< gallery folder="photos">}}
- Fernando_Spadea.jpg
  Fernando Spadea
  PhD Student
- Maruf_Ahmed_Mridul.jpeg
  Maruf Ahmed Mridul
  PhD Student
- Md_Saikat_Islam_Khan_Bappy.jpg
  Md Saikat Islam Khan
  PhD Student
{{</ gallery >}}
