# Exercises

Det regex som ni skriver ska matcha alla inputs i övningen.
Kopiera över hela input-texten till regex101.com och skriv
sedan ditt regex i regular expression-rutan.

Eftersom ```.*``` matchar alla rader måste vi också ha
något som du inte får matcha. Uppgiften är därför att
matcha alla rader i input ovanför ```---``` samtidigt
som du inte får matcha någon av raderna under ```---```.

Exempel:
```
regex: aabb

aabb
---
abb
aab
aa
```

Se till att flaggorna "global" och "multi line" är valda.
De ska vara det som standard så du borde inte behöva tänka
på det.

## Exercise 1

### Inputs

```
aaa
---
a
aa
```

### Regex (ditt svar)

?

## Exercise 2

### Inputs

```
123123123
123123
---
111
222
333
121212121
```

### Regex (ditt svar)

?

## Exercise 3

### Inputs

```
qwe ewq wqe
wqe qwe ewq
ewq qwe wqe
---
qwe ewq
qwe wqe eqw
```

### Regex (ditt svar)

?

## Exercise 4

### Inputs

```
bbb a
bbb aa
bbb aaaaaaa
---
a
bbb
bb a
```

### Regex (ditt svar)

?

## Exercise 5

### Inputs

```
adam@gmail.com
berit@hotmai.com
charlie@mail.co.uk
---
@gmail.com
berit
@
david@hotmail
```

### Regex (ditt svar)

?

## Exercise 6

### Inputs

```
<span>some content</span>
<span class="sidebar">some other content</span>
<span class="sidebar" data-key="value1"></span>
---
<div>some content</div>
<p class="sidebar">some other content</p>
```

### Regex (ditt svar)

?
