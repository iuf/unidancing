# UniDancing Competition Rules (Draft)
__! Under Development !__

## English
New Competition rules for UniDancing (formerly known as Individual/Pair/Group Freestyle). They are currently in draft and it is the early stage for them. They are only available in german so far. An english translation will be available until Unicon, with more information here.

## German

Die Regeln befinden sich in [rules-de.md](blob/master/rules-de.md), dazu auch bitte die Anmerkungen ([annotations-de.md](blob/master/annotations-de.md)) lesen.

## Todo

- Collect video for test routines
- Select 
- Create testdata format
- Create testdata
- Simulate various calculations for the final score
- Create test matrix to evaluate different scenarios

## Tests

- Different weight for masteries (adjustment movements, major and minor dismounts)
- Make mastery dependend on number of tricks

## Testformat

This is how a testfile for one routine could look like (yaml format):

```
rider: Kazuhiro Shimoyama
event: Unicon 16 Brixen
year: 2012
duration: 360

tricks:
	trick:
		name: Arabesque
		time: 240
		difficulty: 8.5
		quality: 8

	...

mastery:
	penalty:
		type: major dismount
		time: 120
		
	penalty:
		type: adjustment
		time: 60

	...


choreography:
	...

artistics:
	...
			
```

### Questions

What are proper variables for artistics and choregraphy


