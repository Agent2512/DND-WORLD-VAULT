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
	let texts = [
		"need to make (characters) folder",
		"need to have characters in the (characters) folder"
	]
	
	dv.list(texts)
}
```
  