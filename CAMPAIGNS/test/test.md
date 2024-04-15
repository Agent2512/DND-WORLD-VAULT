---
GAME-MASTER:
---
# Characters
```dataviewjs
try {
    let cur = dv.current()
    let list = dv.pages(`"CAMPAIGNS/${cur.file.name}/Characters"`)
    dv.list(list.file.link)
} catch (error) {
	console.log(error)
    dv.paragraph("need to make characters folder")
}
```
