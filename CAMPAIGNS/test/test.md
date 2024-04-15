---
GAME-MASTER:
---
# Characters
```dataviewjs
let cur = dv.current()
let list = dv.pages(`"CAMPAIGNS/${cur.file.name}/Characters"`)
if (list.length) {
	dv.list(list.file.link)
}
else {
	dv.paragraph("need to make characters folder or put a character file in folder")
}
```
