---
GAME-MASTER: "[[Foxidize]]"
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
---
it start s on the 2024-04-17 in the city of [[xyz]] 