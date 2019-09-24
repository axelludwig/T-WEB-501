---
title: "{{ replace .Name "-" " " | title }}"

add: "test"
postalCode: "75000"
city: "Paris"
label: "Label"

when: {{ now.Format "2006-01-02" }}
description: "Description"
photos: ["test.jpg"]

draft: true
important: false
association: "les maçons oui"
---
