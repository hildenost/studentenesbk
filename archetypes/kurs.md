---
title: "{{ replace .Name "-" " " | title }}"
order: 0
date: {{ .Date }}
draft: false
type: "kurs"
---
{{< lead >}}
Intro paragraph
{{< /lead >}}

Other intro paragraph

{{ toc }}
