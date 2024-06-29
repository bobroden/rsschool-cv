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
### Work experience
1. June 2022 - June 2023: Junior Developer;
2. June 2023 - October 2023: Developer;
3. October 2023 - present: Engineer.
---
### Education
1. 2017-2021: N. I. Lobachevsky National Research University. Applied Computer Science - Bachelor's degree.
2. 2021-2023: Bauman Moscow State Technical University. Applied Computer Science - Master's degree.
3. 2023-2026: IPU RAS named after V. A. Trapeznikov. Mathematical and software support of computer systems, complexes and computer networks - postgraduate course.

* 2020. Immersion in Python - Coursera;
* 2020. JavaScript, Part 1: Basics and Functions - Coursera;
* 2020. RS 2020 Q1 - RS-School;
* 2021. Frontend development (Angular) - Netcracker, N. I. Lobachevsky National Research University;
* 2022. Frontend development is Netcracker.
---
