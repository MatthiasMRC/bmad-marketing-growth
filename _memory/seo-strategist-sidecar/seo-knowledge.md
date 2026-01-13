# SEO Knowledge Base

> Base de connaissances SEO pour Quinn Crawler.
> Checklists, best practices, et guidelines actualisees.

---

## Core Web Vitals - Checklist

### LCP (Largest Contentful Paint) < 2.5s
- [ ] Optimiser les images (WebP, lazy loading)
- [ ] Preload des ressources critiques
- [ ] CDN pour assets statiques
- [ ] Eliminer render-blocking resources

### FID (First Input Delay) < 100ms
- [ ] Minimiser JavaScript tiers
- [ ] Code splitting
- [ ] Defer non-critical JS
- [ ] Web Workers pour taches lourdes

### CLS (Cumulative Layout Shift) < 0.1
- [ ] Dimensions explicites sur images/videos
- [ ] Reserve espace pour ads/embeds
- [ ] Eviter insertions dynamiques au-dessus du fold
- [ ] Font-display: swap pour web fonts

---

## E-E-A-T Guidelines

### Experience
- Contenu cree par quelqu'un avec experience directe du sujet
- Preuves d'utilisation/test des produits recommandes
- Anecdotes et insights personnels

### Expertise
- Auteur avec credentials verifiables
- Citations de sources autoritaires
- Profondeur technique appropriee au sujet

### Authoritativeness
- Backlinks de sites de reference du domaine
- Mentions dans la presse specialisee
- Profils auteur complets avec bio

### Trustworthiness
- HTTPS obligatoire
- Politique de confidentialite claire
- Informations de contact visibles
- Sources citees et verifiables

---

## Audit Technique - Checklist Complete

### Indexation
- [ ] robots.txt accessible et correct
- [ ] Sitemap XML soumis a GSC
- [ ] Pas de pages importantes en noindex
- [ ] Canonical tags corrects

### Architecture
- [ ] Structure URL logique et plate
- [ ] Breadcrumbs implementes
- [ ] Maillage interne coherent
- [ ] Pas de pages orphelines

### On-Page
- [ ] Title unique < 60 caracteres
- [ ] Meta description unique < 160 caracteres
- [ ] H1 unique par page
- [ ] Hierarchie H1-H6 logique
- [ ] Alt text sur images

### Performance
- [ ] TTFB < 200ms
- [ ] Page size < 3MB
- [ ] Requests < 100
- [ ] Compression GZIP/Brotli

### Mobile
- [ ] Mobile-first indexing ready
- [ ] Viewport meta tag
- [ ] Touch targets > 48px
- [ ] Pas de contenu cache sur mobile

---

## Topic Cluster - Template

```
                    [PILLAR PAGE]
                    /     |     \
                   /      |      \
            [CLUSTER]  [CLUSTER]  [CLUSTER]
              /|\        /|\        /|\
             / | \      / | \      / | \
           [Sub-topics interconnectes]
```

### Structure Recommandee
- **Pillar:** 3000-5000 mots, couvre le sujet en largeur
- **Clusters:** 1500-2500 mots, approfondit un aspect
- **Liens:** Pillar ↔ Clusters (bidirectionnel)
- **Ancres:** Variees, naturelles, descriptives

---

## Intent de Recherche - Classification

| Intent | Signaux | Type de Contenu |
|--------|---------|-----------------|
| **Informationnel** | comment, pourquoi, qu'est-ce que | Guide, tutoriel, article |
| **Navigationnel** | [marque] + login/site/app | Page produit, homepage |
| **Transactionnel** | acheter, prix, meilleur, comparatif | Landing page, comparatif |
| **Commercial** | avis, vs, alternative a | Review, comparatif |

---

## Quick Wins - Categories Communes

### Facile (< 1 jour)
- Optimiser titles/meta descriptions des top 20 pages
- Ajouter alt text manquants
- Corriger liens casses internes
- Ajouter schema markup basique

### Moyen (1-3 jours)
- Creer maillage interne strategique
- Optimiser images (compression, WebP)
- Ameliorer Core Web Vitals
- Enrichir contenu thin

### Impact Eleve
- Pages position 4-10 → potentiel top 3
- Pages avec CTR bas vs position
- Keywords a fort volume, faible difficulte
- Content gaps vs concurrents directs

---

## Metriques Cles a Tracker

| Metrique | Outil | Frequence |
|----------|-------|-----------|
| Positions | GSC, Ahrefs | Hebdo |
| Trafic organique | GA4 | Hebdo |
| Core Web Vitals | PageSpeed | Mensuel |
| Backlinks | Ahrefs, Moz | Mensuel |
| Indexation | GSC | Hebdo |
| CTR par page | GSC | Mensuel |
