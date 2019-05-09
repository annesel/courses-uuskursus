---
title: 'Chapter Title Here'
description: 'Chapter description goes here.'
---

## Example coding exercise

```yaml
type: NormalExercise
key: 2bafef99a3
lang: r
xp: 100
skills: 1
```

This is an example exercise. Ehk esimene näide.

`@instructions`
- Arvuta järgmine summa: 5 + 9 + 40
- jaga tulemus pooleks

`@hint`


`@pre_exercise_code`
```{r}

```

`@sample_code`
```{r}
# summa 
___ + ___ + ___
# jagamine
___ / ___
```

`@solution`
```{r}
# summa 
5 + 9 + 40
# jagamine
54 / 2
```

`@sct`
```{r}
# esimene
test_output_contains("5 + 9 + 40", times = 1, incorrect_msg = "viga esimeses!")
 

# teine
test_output_contains("54/2", times = 1, incorrect_msg = "viga teises!")
success_msg("Tubli! Katsetamise ülesanne on tehtud, asu nüüd päris ülesandeid lahendama!")

```
