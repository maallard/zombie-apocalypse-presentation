---

# Stop the Zombie Apocalypse!

#### Démonstration Kata Codewars


---
`matrix` (carte de base)
```
| 5 | 1 | 9 |
| 5 | 1 | 0 |
| 5 | 5 | 5 |
| 5 | 2 | 6 |
| 5 | 4 | 5 |
| 5 | 9 | 0 |
```
`zombieMap` (carte vierge)
```
| 0 | 0 | 0 |
| 0 | 0 | 0 |
| 0 | 0 | 0 |
| 0 | 0 | 0 |
| 0 | 0 | 0 |
| 0 | 0 | 0 |
```

---
###### Itération 0
`matrix`
```
|*5*| 1 | 9 |
| 5 | 1 | 0 |
| 5 | 5 | 5 |
| 5 | 2 | 6 |
| 5 | 4 | 5 |
| 5 | 9 | 0 |
```
`zombieMap`
```
| 1 | 0 | 0 |
| 0 | 0 | 0 |
| 0 | 0 | 0 |
| 0 | 0 | 0 |
| 0 | 0 | 0 |
| 0 | 0 | 0 |
```

+++

###### Itération 1
`matrix`
```
| 5 |*1*| 9 |
|*5*| 1 | 0 |
| 5 | 5 | 5 |
| 5 | 2 | 6 |
| 5 | 4 | 5 |
| 5 | 9 | 0 |
```
`zombieMap`
```
| 1 | 0 | 0 |
|*1*| 0 | 0 |
| 0 | 0 | 0 |
| 0 | 0 | 0 |
| 0 | 0 | 0 |
| 0 | 0 | 0 |
```

+++
###### Itération 2
`matrix`
```
|*5*| 1 | 9 |
| 5 |*1*| 0 |
|*5*| 5 | 5 |
| 5 | 2 | 6 |
| 5 | 4 | 5 |
| 5 | 9 | 0 |
```
`zombieMap`
```
| 1 | 0 | 0 |
| 1 | 0 | 0 |
|*1*| 0 | 0 |
| 0 | 0 | 0 |
| 0 | 0 | 0 |
| 0 | 0 | 0 |
```

+++
###### Itération 3
`matrix`
```
| 5 | 1 | 9 |
|*5*| 1 | 0 |
| 5 |*5*| 5 |
|*5*| 2 | 6 |
| 5 | 4 | 5 |
| 5 | 9 | 0 |
```
`zombieMap`
```
| 1 | 0 | 0 |
| 1 | 0 | 0 |
| 1 |*1*| 0 |
|*1*| 0 | 0 |
| 0 | 0 | 0 |
| 0 | 0 | 0 |
```

+++
###### Itération 4
`matrix`
```
| 5 | 1 | 9 |
| 5 |*1*| 0 |
|*5*| 5 |*5*|
| 5 |*2*| 6 |
|*5*| 4 | 5 |
| 5 | 9 | 0 |
```
`zombieMap`
```
| 1 | 0 | 0 |
| 1 | 0 | 0 |
| 1 | 1 |*1*|
| 1 | 0 | 0 |
|*1*| 0 | 0 |
| 0 | 0 | 0 |
```

+++
###### Itération 5
`matrix`
```
| 5 | 1 | 9 |
| 5 | 1 | 0 |
| 5 | 5 | 5 |
|*5*| 2 | 6 |
| 5 |*4*| 5 |
|*5*| 9 | 0 |
```
`zombieMap`
```
| 1 | 0 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |
| 1 | 0 | 0 |
| 1 | 0 | 0 |
|*1*| 0 | 0 |
```

+++
## Merci pour votre attention

#### Questions ?

Liens :
- https://www.codewars.com/kata/stop-the-zombie-apocalypse
- solution kata par @increscent : https://www.codewars.com/kata/reviews/5464e33b24b6c23707000198/groups/55689b4e864bdf05d9000019
