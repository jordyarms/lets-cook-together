---
date: {{date}}
attendees: 
recipies: 
tags:
  - type/instance
---

## Shopping List
```dataview
TASK
FROM outgoing([[]])
WHERE !completed
GROUP BY file.link
```

