# Le Dossier noir de la Belgique

Une chronologie commentée et sourcée des crises, scandales et zones d'ombre de l'histoire de la Belgique — de la révolution brabançonne de 1789 au Qatargate de 2022.

**Site en ligne →** https://ouaisfieu.github.io/belgique/

Document de synthèse à vocation pédagogique. Sources citées en regard de chaque fiche et dans la note méthodologique.

---

## Contenu

| Page | URL | Description |
|------|-----|-------------|
| **Le Dossier noir** | [`/`](https://ouaisfieu.github.io/belgique/) | La chronologie principale : 22 affaires, 6 époques, 1789 → 2022 |
| **Faire tenir la Belgique** | [`/faire-tenir.html`](https://ouaisfieu.github.io/belgique/faire-tenir.html) | Essai sur la construction de l'État belge |
| **Faire tomber la Belgique** | [`/faire-tomber.html`](https://ouaisfieu.github.io/belgique/faire-tomber.html) | Le réquisitoire — l'argument pour la fin de l'État belge |
| **Le Forage** | [`/le-forage.html`](https://ouaisfieu.github.io/belgique/le-forage.html) | Sous les scandales, la machine : neuf strates de la particratie |
| **Le Peuple c. la Particratie** | [`/le-requisitoire.html`](https://ouaisfieu.github.io/belgique/le-requisitoire.html) | Réquisitoire citoyen monté comme un dossier judiciaire |
| **La démocratie sous cloche** | [`/democratie-sous-cloche.html`](https://ouaisfieu.github.io/belgique/democratie-sous-cloche.html) | Anatomie structurelle de la particratie belge |

## Structure du dépôt

```
.
├── index.html                     # page d'accueil (Le Dossier noir)
├── faire-tenir.html               # essais
├── faire-tomber.html
├── le-forage.html
├── le-requisitoire.html
├── democratie-sous-cloche.html
├── assets/                        # favicons + images de partage (Open Graph)
│   ├── favicon.svg / .ico
│   ├── apple-touch-icon.png
│   └── og-*.png
├── sitemap.xml                    # plan du site (URLs canoniques)
├── robots.txt
├── 404.html                       # page d'erreur sur mesure
├── .nojekyll                      # sert le site tel quel (pas de build Jekyll)
└── google…​.html                   # vérification Google Search Console
```

## Référencement (SEO)

Chaque page porte :

- une balise **`<link rel="canonical">`** (URL de référence unique) ;
- des métadonnées **Open Graph** et **Twitter Card** + une image de partage dédiée (1200×630) ;
- des **données structurées JSON-LD** (`Article` / `WebSite`, schema.org) ;
- un **favicon** (tricolore belge vieilli) et une couleur de thème.

Un `sitemap.xml` et un `robots.txt` sont déclarés et soumis à Google Search Console.

### Note sur les fichiers dupliqués

Les fichiers `etat-belge.html`, `etat-belge-bis.html`, `1/index.html` et `2/index.html`
sont des copies **identiques** de `faire-tenir.html`. Pour éviter le contenu dupliqué,
ils portent une balise `noindex` + un `canonical` pointant vers `faire-tenir.html`.

> 💡 Le plus propre serait de **supprimer** ces quatre fichiers et de ne garder que
> `faire-tenir.html`. Ils ne sont conservés que par sécurité (au cas où d'anciens liens
> pointeraient encore vers eux).

## Licence / usage

Travail de vulgarisation. Toute correction documentée est la bienvenue (issues / pull requests).
