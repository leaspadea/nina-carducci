# 📸 Nina Carducci — Optimisation SEO & performances

> Optimisation du référencement naturel (SEO), des performances et de l'accessibilité du site portfolio de Nina Carducci, photographe portraits et événementiel à Bordeaux. Refonte technique sans altération du rendu visuel ni des fonctionnalités existantes.

## 🚀 Démo en ligne

👉 **[Voir le site en ligne](https://leaspadea.github.io/nina-carducci/)**

📄 **[Rapport d'optimisation (PDF)](https://leaspadea.github.io/nina-carducci/rapport/rapport-optimisation.pdf)**

## 🎯 Contexte du projet

Nina Carducci, photographe à Bordeaux, dispose d'un site portfolio mono-page qui se charge lentement et n'est pas optimisé pour les moteurs de recherche. Elle souhaite améliorer sa visibilité en ligne sans changer l'apparence de son site.

**Mission :** auditer puis optimiser le site existant sur trois axes — **performances**, **référencement (SEO)** et **accessibilité** — en s'appuyant sur des audits Lighthouse et WAVE, sans casser les fonctionnalités en place (carrousel, galerie filtrable, formulaire). Le projet inclut la production d'un rapport d'optimisation détaillant les actions menées et leur impact.

## 🛠️ Technologies utilisées

- **HTML5** — structure sémantique
- **CSS3** — styles du site
- **Bootstrap 5.1.3** — carrousel du header
- **jQuery 3.4.1** — dépendance du plugin de galerie
- **maugallery** — plugin de galerie filtrable par catégories
- **Schema.org** — données structurées pour le référencement local
- **Git / GitHub** — versioning

## ⚡ Optimisations réalisées

- ✅ **Performances** : compression et conversion des images (WebP), attributs `width`/`height`, `loading="lazy"`, `defer` sur les scripts
- ✅ **SEO technique** : `title`, `meta description`, attribut `lang`, balisage HTML5 sémantique, attributs `alt` descriptifs
- ✅ **Référencement local** : données structurées Schema.org (LocalBusiness)
- ✅ **Réseaux sociaux** : balises Open Graph et Twitter Cards
- ✅ **Accessibilité** : liaison des `<label>` aux champs, hiérarchie des titres, contrastes, navigation clavier

## 📊 Résultats (Lighthouse, Desktop)

| Axe | Avant | Après |
|---|---|---|
| Performances | 74 | 98 |
| Accessibilité | 70 | 100 |
| SEO | 73 | 100 |
| Poids des images | 29,4 Mo | 0,7 Mo (−98 %) |

## 📐 Structure du projet

```text
nina-carducci/
├── assets/
│   ├── bootstrap/        # Bootstrap 5.1.3 (CSS + JS)
│   ├── images/
│   │   ├── gallery/      # photos de la galerie, classées par catégorie
│   │   └── slider/       # photos du carrousel
│   ├── maugallery.js     # plugin de la galerie filtrable
│   ├── scripts.js        # initialisation des scripts
│   └── style.css         # styles du site
├── index.html
├── README.md
└── .gitignore
```

## 🎓 Compétences travaillées

- Réalisation d'**audits de performance et de qualité** avec Lighthouse et WAVE
- Optimisation des **performances web** : poids des images, formats modernes, chargement différé
- **Référencement naturel (SEO)** technique : balises meta, sémantique HTML, attributs `alt`
- Mise en place de **données structurées** Schema.org pour le référencement local
- Intégration des balises **Open Graph** et **Twitter Cards**
- Amélioration de l'**accessibilité** (WCAG) : labels, contrastes, navigation clavier
- Rédaction d'un **rapport d'optimisation** à destination d'un client non technique

## 📦 Prérequis

- Un navigateur web moderne (Chrome, Firefox)
- [Visual Studio Code](https://code.visualstudio.com/) avec l'extension **Live Server** (pour le développement)

## 🚀 Installation

Le site est entièrement **statique** : aucune dépendance ni build à installer.

```bash
git clone https://github.com/leaspadea/nina-carducci.git
cd nina-carducci
```

Ouvrir ensuite `index.html` dans un navigateur, ou via l'extension **Live Server** de VS Code (clic droit sur `index.html` → *Open with Live Server*) pour bénéficier du rechargement automatique.

## 👤 Auteur

**Léa Spadea** — Étudiante Intégratrice Web @ OpenClassrooms
🔗 [LinkedIn](https://www.linkedin.com/in/lea-spadea/) · 💻 [GitHub](https://github.com/leaspadea)

## 📄 Licence

Le **code** de ce projet est distribué sous licence **MIT**.

Les **photographies** et le contenu éditorial du site restent la propriété de Nina Carducci et ne sont pas couverts par cette licence.

---

*Projet réalisé dans le cadre de la formation Intégrateur Web (RNCP niveau 5) chez OpenClassrooms.*
