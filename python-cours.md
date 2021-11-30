
# Exercice 1

Coriger les erreurs de syntaxe

```python
print('Bonjour tout le monde !")
print('Je m'appelle Patrick.')
print("Je dis souvent "la vie est un long fleuve tranquille" quand on s'appelle Patrick.")
print(Oui, je suis très philosophe.)

a = -2..5
b = true
c = falce
d = Bonjour tout le monde
```
Solution :
```python
print("Bonjour tout le monde !")
print("Je m'appelle Patrick.")
print("Je dis souvent la vie est un long fleuve tranquille quand on s'appelle Patrick.")
print("Oui, je suis très philosophe.")

a = -2.5
b = True
c = False
d = "Bonjour tout le monde"
```


# Exercice 2

Proposer aux élèves de faire une calculatrice qui :

- Demande un premier nombre à l'utilisateur
- Demande une deuxième nombre à l'utilisateur
- Additionne les nombres
- Affiche les nombres

Solution :
```python
nb1 = int(input("Premier Nombre : "))
nb2 = int(input("Deuxieme Nombre : "))
print(nb1+nb2)
```

# Exercice 3
Dans cet exercice, vous devrez modifier la variable URL pour quelle contienne la chaine de caractères : [https://www.python.org/doc/](https://www.python.org/doc/)
```python
# Ne modifiez pas les variables ci-dessous
protocole = "https://"
nom_du_site = "python"
extension = "org"
page = "doc"

# Modifiez le code à partir d'ici 
URL = f""
```
Solution :
```python
# Modifiez le code à partir d'ici 
URL = f"{protocole}www.{nom_du_site}.{extension}/{page}/"
print(URL)
```

# Exercice 4
1.
Récupérez le premier et le dernier nombre contenus dans cette liste dans les variables 'nombre_premier' et 'nombre_dernier'.
```python
nombres = [1, 2, 3, 4, 5, 4, 3, 2, 1]
nombre_premier = 
nombre_dernier =
```
Solution :
```python
nombres = [1, 2, 3, 4, 5, 4, 3, 2, 1]
nombre_premier = nombres[0]
nombre_dernier = nombres[-1]
print(nombre_premier)
print(nombre_dernier)
```
2. 
Récupérer l'élément 'Python' contenu dans la liste dans la variable 'langage'.
```python
langages = ["Java", "Python", "C++"]
langage =
```
Solution :
```python
langages = ["Java", "Python", "C++"]
langage = langages[1]
print(langage)
```
3. 
Changez la position de l'élément 'Python' dans la liste pour qu'il se retrouve à la fin de la liste (["Java", "C++", "Python"])
```python

liste = ["Java", "Python", "C++"]
```
Solution :
```python
liste = ["Java", "Python", "C++"]
liste.remove[("Python")]
liste.append("Python")
print(liste)
```
4. 
L'objectif de cet exercice est de récupérer les informations suivantes grâce aux slices :

- Les trois premiers employés ("Maxime", "Martine" et "Christopher") dans une liste "trois_premiers"
- Les trois derniers employés ("Carlos", "Michael" et "Éric") dans une liste "trois_derniers"
- Tous les employés sauf le premier et le dernier dans une liste "milieu"
- Le premier et le dernier employé dans une liste "premier_dernier
```python
liste = ["Maxime", "Martine", "Christopher", "Carlos", "Michael", "Eric"]
trois_premiers = # INSÉRER CODE ICI
trois_derniers = # INSÉRER CODE ICI
milieu = # INSÉRER CODE ICI
premier_dernier = # INSÉRER CODE ICI
```
Solution :
```python

liste = ["Maxime", "Martine", "Christopher", "Carlos", "Michael", "Eric"]
trois_premiers = liste[0:3]
print(trois_premiers)
trois_derniers = liste[-3:]
print(trois_derniers)
milieu = liste[2:4]
print(milieu)
premier_dernier = liste[::5]
print(premier_dernier)
```
5. 
Dans cet exercice vous devrez : 

- Ajouter le nombre 6 à la liste
- Faire une vérification par la suite pour vérifié qu'il a bien été ajouté
```python
liste = [1, 2, 3, 4, 5]
```
Solution :
```python
liste = [1, 2, 3, 4, 5]
liste.append(6)
if 6 in liste:
    print("OK")
```
6. 
Dans cet exercice, vous allez devoir récupérer les informations à l'intérieur de listes imbriquées.
```python
langages = [["Python", "C++"], "Java"]
nombres = [1, [4, [2, 3]], 5, [6], [[7]]]

python = # entrez le code ici
deux = # entrez le code ici
sept = # entrez le code ici
```
Solution :
```python
langages = [["Python", "C++"], "Java"]
nombres = [1, [4, [2, 3]], 5, [6], [[7]]]

python = langages[0][0]
deux = nombres[1][1][0]
sept = nombres[-1][-1][-1]

print(python)
print(deux)
print(sept)
```

# Les Boucles
## Exercice 1 

Solution :
```python
for loop in range(1, 11):
    print("Utilisateur ", loop)
```
## Exercice 2
```python
mot = "Python"
for i in mot[::-1]:
    print(i)
```
## Exercice 3
```python
mot = "Python"
for i in range(len(mot)):
    print(i)
```
## Exercice 4
```python
nombre = 7
for i in range(10):
    print(f"{i} x {nombre} = {i*nombre}")
```
## Exercice 5
```python
i = 0
while i < 10:
	break
resultat = "Exercice réussi !"
```
## Exercice 6
```python
continuer = "o"
while continuer == "o":
    print("On continue !")
    continuer = input("Continuer o/n")
    if continuer != "o":
        break
```
## Exercice 7
```python
nombres = list(range(51))
nombres_pairs = nombres[::2]
print(nombres_pairs)
```
# Fonctions
## Exercice 1
```python
def saluer(name):
    print(name)
saluer("Patrick")
```
## Exercice 2
```python
def multiplicateur_mot(mot):
    mult=0
    for mult in range(5):
        print(mot)
mot_multiplie = multiplicateur_mot("Bonjour")
print(mot_multiplie)
```
## Exercice 1
```python
def addition(a, b):
    return a+b
resultat = addition(5, 10)
print(resultat)
```
```python

```
```python

```

### Syntax
```python
<code>
```
