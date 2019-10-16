---
title: ' Sissejuhatus'
description: 'Chapter description goes here.'
---

## Näiteülesanne

```yaml
type: NormalExercise
key: 2bafef99a3
lang: r
xp: 100
skills: 1
```

Kirjuta kõigi ülesannete lahendused paremal aknapoolel olevasse *SCRIPT.R* lehele, vastava ülesande sõnastuse alla. Siinses näites on esimese ülesande lahendus juba kirja pandud.

Ühe vastuse väljaarvutamiseks või testimiseks pane *SCRIPT.R* lehel hiirekursor vastava rea peale ja vajuta klahvikombinatsiooni `Ctrl+Enter`, 
sellega saadetakse vastav rida allpool olevale R-i konsoolile täitmiseks. Kogu koodi täitmiseks vajuta nuppu `Run Code`, sama nupuga saab koodi konsoolile saata ka rida või plokk haaval, siis aga peaks vastav osa koodist hiirega aktiivseks valitud olema. Konsooli käsurida võid ka kasutada: kirjuta käsk ning vajuta täitmiseks `Enter`-klahvi. Proovi siin ülesandes need võimalused läbi.

Lahenduse vihjete saamiseks vajuta nuppu `Take Hint`, aga sellega kaotad võimalikke punkte! Kui oled lahti teinud vihjed, siis võid edasi avada ka kogu lahenduse koodi, kuid nii toimides lähevad ülesande punktid nulli.

Oma vastuse esitamiseks vajuta `Submit Answer`-nuppu, siis saadetakse ülesanded kontrollimiseks. Vajuta seda nuppu siis kui oled kirja pannud kõik selle lehekülje ülesannete vastused.

`@instructions`
**Prooviülesanne (0 punkti):**

- Liida arvud 3 ja 4.
- Omista väärtus 9 muutujale `x`.

`@hint`
- Liitmiseks kasuta märki `+` või funktsiooni `sum`
- Omistamiseks kasuta kombinatsiooni `<-`

`@pre_exercise_code`
```{r}

```

`@sample_code`
```{r}
# Liida
3 + 4

# Omista

```

`@solution`
```{r}
# Liida
3 + 4

# Omista
x <- 9
```

`@sct`
```{r}
# esimene
check_output_expr(state = ex(),expr = "3 + 4",   times = 1, missing_msg = "Oled esimeses ülesandes õige vastuse valeks parandanud. Alusta uuesti!")
ex() %>% check_code("3",  missing_msg = "Kontrolli, kas esimese ülesande tehe on kujul `3 + 4`!")
ex() %>% check_code("4",  missing_msg = "Kontrolli, kas esimese ülesande tehe on kujul `3 + 4`!")
 
# teine
ex() %>% check_object("x") %>% check_equal()
#("x",  undefined_msg = "Vali muutuja nimeks `x`.",  incorrect_msg = "Omistasid muutujale  `x` vale väärtuse. Proovi uuesti!")


success_msg("Tubli! Katsetamise ülesanne on tehtud, asu nüüd päris ülesandeid lahendama!")


 
```

---

## Insert exercise title here

```yaml
type: BulletExercise
key: ad3b09f09f
xp: 100
```



`@pre_exercise_code`
```{r}

```
