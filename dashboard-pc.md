---
cssclasses:
  - dashboard
---

---
# Your Personal Curriculum
- MONTH - Course#: Course name 
	- [x] Book: 
	- [ ] Book: 
	- [ ] Video: 
  - [ ] Course: 

- MONTH - Course#: Course name 
	- [ ] Book: 
	- [ ] Book: 
	- [ ] Video: 
  - [ ] Course: 

- DAY - Course#: Course name 
	- [ ] Book: 
	- [ ] Book: 
	- [ ] Video: 
  - [ ] Course: 

- ONGOING - Course#: Course name 
	- [ ] Book: 
	- [ ] Book: 
	- [ ] Video: 
  - [ ] Course: 


 # Todos
- ☀️ Today
`$=dv.list(dv.pages('#today').sort(f=>f.file.name,"desc").limit(10).file.link)`

- 📆 This Week
`$=dv.list(dv.pages('#thisweek').sort(f=>f.file.name,"desc").limit(10).file.link)`

- 🗓️ Next Week
`$=dv.list(dv.pages('#nextweek').sort(f=>f.file.name,"desc").limit(10).file.link)` 

- ▶️ In progress
`$=dv.list(dv.pages('#inprogress').sort(f=>f.file.name,"desc").limit(10).file.link)`


# Vault Info
- 🗄️ Recent file updates
 `$=dv.list(dv.pages('').sort(f=>f.file.mtime.ts,"desc").limit(5).file.link)`
- 💟 Tagged:  Favorites 
 `$=dv.list(dv.pages('#favorite').sort(f=>f.file.name,"desc").limit(10).file.link)` 
- 📝 Tagged:  Journal 
 `$=dv.list(dv.pages('#journal').sort(f=>f.file.name,"desc").limit(10).file.link)`
- 〽️ Stats
	-  File Count: `$=dv.pages().length`
	-  Daily notes: `$=dv.pages('"_Quick Notes/Journals/2025/Daily"').length` 
