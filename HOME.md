# CAMPAIGNS
```dataviewjs 
let list = dv.pages('"CAMPAIGNS"').filter(e => {
	let f = e.file.folder.split("").filter(i => i == "/")
	
	if (f.length > 1) return false

	return true
})

dv.list(list.file.link)
```

