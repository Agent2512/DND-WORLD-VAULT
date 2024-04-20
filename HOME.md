# CAMPAIGNS
```dataviewjs 
let list = dv.pages('"CAMPAIGNS"').filter(e => {
	let folder = e.file.folder.replaceAll('"', '').split('/')[1]
	let fileName = e.file.name.replaceAll('"', '')

	if (folder == fileName) return true

	console.log(fileName)
	return false
})

dv.list(list.file.link)
```


![[Village Idiot Name Generator.webp]]