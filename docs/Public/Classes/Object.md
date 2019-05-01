# Object class

La classe de base héritée par toutes les class . Expose des fonctions basiques, telles que `getId`, `getType`, `equals`, et `toString`.

### Définition interne

```ruby
public class System.Object
```

### Hérite de

Aucune classes.

### Héritée par

Toutes les classes.

## Méthodes & Constructeurs

### Contructeurs

| Nom              | Description                    | Accessibilité |
| ---------------- | ------------------------------ | ------------- |
| Object()         | Créer un nouvel object.        | public        |
| Object(Object o) | Créer un objet à partir de `o` | public        |

Note : Le constructeur `Object()` de cette classe est implicite.

Note : Le constructeur `Object(Object o)` est utilisé lors d'un cast à ce type.

### Méthodes

| Nom                    | Description                                                                                         | Type du résultat | Accessibilité |
| ---------------------- | --------------------------------------------------------------------------------------------------- | ---------------- | ------------- |
| equals(Object)         | Retourne `true` si l'objet passé est égal à l'objet actuel. Retourne `false` dans le cas contraire. | bool             | public        |
| equals(Object, Object) | Retourne `true` si les deux objets passés sont égaux. Retourne `false` dans le cas contraire        | bool             | public static |
| getId()                | Retourne l'ID de l'objet.                                                                           | string           | public        |
| getType()              | Retourne le Type de l'objet                                                                         | Type             | public        |
| toString()             | Retourne une chaîne (`string`) qui représente l'objet actuel.                                       | string           | public        |

## Exemples

```ruby
# Un ou plusieurs exemples d'utilisation de cette classe
```

## Remarques

Étant donné que cette classe est une classe de base, n'importe quel instance peut être castée à ce type. 

De plus, cela signifie que n'importe classes contient les méthodes de ce type. Cependant, certaines classes pourraient overrider ces mpéthodes. Merci de vous référer à la documentation de ces classes pour plus d'informations.

## Historique & disponibilité

Disponible depuis version 0.1

Aucun changement majeur depuis.