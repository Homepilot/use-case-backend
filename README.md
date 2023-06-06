# Cas technique Backend 🛠️

Le but du cas technique est de réaliser des routes API ainsi que la construction de la base de données. Il est à réaliser en 3h maximum. Nous attendons de vous que vous réalisiez le cas technique avec le framework NestJS ainsi qu'une base de données relationelle.

##### Pour notre cas technique nous avons 2 entités:

-   les biens
-   les propriétaires

### Voici un exemple regroupant les 2 entités avec leurs attributs:

```json
{
    "id": 1,
    "landlord_id": 1,
    "name": "Appartement 1",
    "surface": 80,
    "furnished": false,
    "rent_amount": 1000,
    "photo_url": "https://example.com/photo1.jpg",
    "created_at": "2023-06-02T13:23:18.020Z",
    "updated_at": "2023-06-05T16:23:40.308Z",
    "landlord": {
        "id": 1,
        "gender": "Male",
        "first_name": "John",
        "last_name": "Doe",
        "created_at": "2023-06-02T13:23:18.017Z",
        "updated_at": "2023-06-02T13:23:18.017Z"
    }
}
```

#### Voici les routes et leurs comportements à reproduire:

```
GET /units
```

> Récupération de tous les biens en intégrant une pagination ainsi que le propriétaire associé

```
POST /units
```

> Création d'un bien

```
PUT /units/:id
```

> Mise à jour d'un bien

```
DELETE /units/:id
```

> Suppression d'un bien

**⚠️ Les routes sont présenté au format REST, cependant vous pouvez utiliser GraphQL si vous le souhaitez.**

---

### 🚀 Clonez/Downloadez le repo puis assignez lui l'URL d'un nouveau repo git que vous aurez créé afin de pouvoir nous le partager.
### Merci de ne pas forker le repo afin de ne pas involontairement partager votre travail avec les autres candidats 😉

Voici les identifiants Github à ajouter en tant que collaborateur:

-   @BenoitStephant
-   @easygreg
-   @Koala-gentil
-   @thibault60000

## Bon courage 🐈 !
