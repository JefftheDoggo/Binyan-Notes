---
title: Dashboard
tags:
  - navigation
obsidianUIMode: preview
cssclasses:
  - dashboard
banner: "![[Homepage.png]]"
banner_y: 0
---
<div class="title" style="color:white">Dashboard</div>

### School
- Finished Notes
`$=dv.list(dv.pages('#finished').sort(f=>f.file.ctime,"desc").limit(5).file.link)`
- Ongoing Work
`$=dv.list(dv.pages('#ongoing').sort(f=>f.file.ctime,"desc").limit(5).file.link)`
- Other
`$=dv.list(dv.pages('#miscschool').sort(f=>f.file.ctime,"desc").limit(5).file.link)`
- [[Subjects - Year 11]]

### Personal Projects
- Conlang
`$=dv.list(dv.pages('#conlang').sort(f=>f.file.ctime,"desc").limit(5).file.link)`
- [[Reviews]]
`$=dv.list(dv.pages('#review').sort(f=>f.file.ctime,"desc").limit(5).file.link)`

### Vault Info
- Recent file updates
`$=dv.list(dv.pages('').sort(f=>f.file.mtime.ts,"desc").limit(4).file.link)`
- Stats
	- File Count: `$=dv.pages().length`