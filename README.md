# Tearea Git Ramas + merge

## Autor:

- Anxo Vázquez Lorenzo

## Este es el commit A

## Este es el commit B

## Este es el commit E

## Este es el commit F

# Commandos

Clonar el repositorio de github:

```
git clone
```

Escribir un `Readme` con una modificación y hacer un `push` al remoto:

```
echo "Este es el commit A" > README.md
git add README.md 
git commit -m "Commit A"
git push
```

Repetir el mismo paso anterior pero para el `commit B`:

```
echo "Este es el commit A" > README.md
git add README.md
git commit -m "Commit A"
git push
```

Cambiar de rama a `exp` y hacer `commit C`:

```
git checkout -b exp #-b crea la rama si es que no existía antes
echo "Este es el commit C" > README2.md
git add README2.md
git commit -m "Commit C"
git push
```

Cambiarse otra vez a la rama `main` y hacer el `commit E`:

```
git checkout main
echo "Este es el commit E" > README.md
git add README.md
git commit -m "Commit E"
git push
```

Volver a la rama `exp` y hacer el `commit D`:

```
git checkout exp
echo "Este es el commit D" > README2.md
git add README2.md
git commit -m "Commit D"
git push
```

Ir a la ramma `main` y hacer el último `commit` (F):

```
git checkout mainn
echo "Este es el commit F" > README.md
git add README.md
git commit -m "Commit F"
git push
```
