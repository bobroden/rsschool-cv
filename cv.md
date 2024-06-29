# Denis Bobrov
---
### Contact information
Email: *bobrow.bobro2015@yandex.ru*
Telegram: *bobroden*
Discord: *bobroden*
---
### Information about yourself
I want to become a frontend developer again. I want to remember everything related to this field, as well as acquire new knowledge that has appeared during my absence. I worked as a frontend developer for about 1.5 years. My strengths are: punctuality, discipline, perfectionism, etc.
---
### Skills
* HTML
* CSS
* SCSS
* JavaScript
* TypeScript
* Angular
* Git
---
### Code examples
```
constructor(public audioTalkService: AudiotalkService, public serverService: ServerService, private router: Router, private store$: Store) {
		if (this.serverService.currentWords.length === 0) {
			const page: string = localStorage.getItem("page");
			const group: string = localStorage.getItem("group");
			if (page === null || group === null) {
				this.router.navigateByUrl("/main");
			}
			this.serverService.page = page;
			this.serverService.group = group;
			this.store$.dispatch(StoreActions.getNewWords());
		}
		this.words$ = this.store$.select(StoreSelectors.currentWords).subscribe((): void => this.serverService.shuffle());
		this.start();
		this.audioTalkService.rightWords = 0;
		this.audioTalkService.wrongWords = 0;
	}
```
---

