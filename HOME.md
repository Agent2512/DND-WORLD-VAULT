# CAMPAIGNS
```dataviewjs 
let list = dv.pages('"CAMPAIGNS"').filter(e => {
	let f = e.file.folder
	

	return true
})

list.map(e => {
console.log("test",e)
return e
})



 
dv.list(list.file.link)
```
