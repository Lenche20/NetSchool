# NetSchool

NetSchool - систем за онлајн учење
Проект по Дизајн интеракција човек-компјујтер.

https://lenche20.github.io/NetSchool/ - Линк до хостираниот систем

Изработено од Ленче Владимирова 191075






## 1.	Опис на системот 

Апликацијата што ја развивам претставува онлајн систем за учење и сертификација и истата е наречена NetSchool. 

NetSchool претставува веб сајт каде корисниците ќе може да учат курсеви, да се тестираат и да се сертифицираат за истите.  
Начинот на навигација е едноставен преку навигациското мени, а има и дополнителни копчиња кои ја олеснуваат навигацијата. 
Корисникот има свој профил - Profile каде се чуваат неговите курсеви и сертификати. 
Од јавната библиотека - Public library корисникот може да одбере нов курс и веднаш може да започне со учење на материјалот. 
Важна функционалност на системот е делот за учење - Learn, бидејќи таму се наоѓаат лекциите за курсевите и од таму се пристапува до делот за тестирање на знаење со кој се добива сертификат. 




## 2. Упатство за користењe

Во системот има 8 различни страни кои се објаснети подолу. 
- 3 страни потребни за стартување на сајтот и најавување на корисникот
- 3 страни кои се поврзани со навигациското мени
- 2 страни за тестирање на знаење и сертификација 


## 3.1 Landing Page

Првата страна и тоа што се појавува веднаш при отворање на апликацијата е Landing Page (index.html во изворниот код). 

На почетниот прозорец (слика 1) при стартување на апликацијата имаме можност: 
да се избере за почеток на играта (СТАРТ), 
да прочитаме упатство/добиеме помош како се игра играта (ПОМОШ) и, се разбира, 
копче за исклучување на играта (ИЗЛЕЗ). 

При кликнување на ИЗЛЕЗ, играта се исклучува.

![Слика 1](https://i.ibb.co/vPSvkg8/Screenshot-2.png)

###### Слика 1


## 3.2 ВТОРА СЦЕНА
При кликнување на ПОМОШ се отвора нова сцена (Слика 2) каде е дадено кратко упатсво за играње на играта. Правила на играта и команди за користење при играта може да се прочитаат во оваа сцена. На оваа сцена има копче за ИЗЛЕЗ, при кое се враќаме на почетниот прозорец (сцена 3.1). 

![Слика 2](https://prnt.sc/YZRJS_bQHzKF)

###### Слика 2

## 3.3 ТРЕТА СЦЕНА
Доколку кликнеме на копчето СТАРТ се започнува играта и ќе се вчита третата сцена, односно сцената каде што се игра играта (Слика 3 и Слика 4). 

Начинот на играње е едноставен. Во играта играчот има функционалности на движење лево и десно со цел пукање кон чудовиштата (Слика 3) и избегнување на куршуми од главните непријатели (Слика 4). 

На сцената, во горниот десен агол, може да се забележи колку парички играчот собрал. 

![Слика 3](https://i.ibb.co/3f0B76m/Screenshot-4.png) 

###### Слика 3

![Слика 4](https://i.ibb.co/jhqMQDf/Screenshot-6.png) 

###### Слика 4

## 3.4 ЧЕТВРТА СЦЕНА
Четвртата сцена се појавува кога играчот умира во играта (Слика 5). 
После секоја игра завршена (секое умирање на играчот) на играчот му се прикажува колку парички освоил. 
Тука може да се види колку парички има собрано играчот и има две копчиња (ЗАПОЧНИ ОДНОВО) каде можеш да избереш да се вратиш на почетната сцена(сцена 3.1) или (ИЗЛЕЗ) да ја исклучиш играта. 

![Слика 5](https://i.ibb.co/100D6fr/Screenshot-5.png)

###### Слика 5


## 4. Правила 

Правилата на играта се следни:

	Играчот има еден живот
	При судар со чудовиште играчот го губи животот и играта завршува
	Играчот го губи животот доколку е погоден од некој од главните непријатели и играта завршува

	Чудовиштата, кои имаат стандарден health, доколку не се убиени едноставно заминуваат од екранот (Слика 3)
	Откако ќе ги испукате чудовиштата (health==0), тие експлодираат во парички
	Паричките треба сам да ги собере играчот  

	Главните непријатели имаат поголем health и не си заминуваат се додека не се убиени (Слика 4)

	После секој убиен главен непријател се зголемува "нивото"
	Паричките кои се појавуваат при експлозија/убивање на чудовиште, се зголемуваат за едно, после секое "ниво"
	Побрзо доаѓаат чудовиштата после секое "ниво"




## 5.	Контроли за игра:
Контролите за играње се едноставни, а движењата се ограничени.

Контроли за игра:
	
	Left Arrow - движење на лево со леталото.
	Right Arrow - движење на десно со леталото.



https://mega.nz/folder/2dxgTbpA#TmFsQ1Kh8LNLLe7rQGBvIw - Линк за превземање на извршена верзија од играта

