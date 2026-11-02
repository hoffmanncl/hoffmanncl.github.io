# Site web — Clément Hoffmann

Site académique basé sur le template [Academic Pages](https://github.com/academicpages/academicpages.github.io) (Jekyll), hébergé sur GitHub Pages.

## Où modifier quoi

Le site tient sur une seule page (`/`) : présentation, puis sections Publications, Talks et Teaching,
générées à partir des collections ci-dessous et triées par date (plus récent en premier).

| Quoi | Fichier |
|---|---|
| Nom, bio, liens (Scholar, GitHub, Zenodo, ORCID, LinkedIn) dans la barre latérale | `_config.yml` (section `author`) |
| Menu du haut | `_data/navigation.yml` |
| Texte de présentation | `_pages/about.md` |
| Publications (un fichier par article : `authors`, `venue`, `eprint`, `tches`, `doi`, `pdf`, `code`, `excerpt`) | `_publications/` |
| Exposés (`type`, `venue`, `location`, `slides`) | `_talks/` |
| Enseignement / encadrement | `_teaching/` |
| Rendu des sections | `_includes/home-publications.html`, `home-talks.html`, `home-teaching.html` |
| Styles ajoutés | fin de `assets/css/main.scss` |
| Photo de profil | `images/profile.png` |
| PDF (CV, slides, articles) | `files/` → accessibles via `/files/nom.pdf` |

Le lien « CV (PDF) » du menu n'apparaît que si `files/cv.pdf` existe.
Les champs vides marqués `TODO` sont visibles (grisés) en local uniquement, jamais sur le site publié.

## Prévisualiser en local

Prérequis (une seule fois) :

```bash
sudo apt install ruby-dev
gem install --user-install bundler
export PATH="$HOME/.local/share/gem/ruby/3.0.0/bin:$PATH"   # à mettre dans ~/.bashrc
bundle config set --local path vendor/bundle
bundle install
```

Puis :

```bash
bundle exec jekyll serve -l
```

et ouvrir <http://localhost:4000>. Le site se recharge à chaque modification
(sauf `_config.yml` : relancer la commande).

## Mise en ligne

1. Créer un dépôt **public** nommé `hoffmanncl.github.io` sur GitHub.
2. Pousser ce dossier sur la branche `main`.
3. Dans *Settings → Pages*, choisir **Source : GitHub Actions**.
4. Le workflow `.github/workflows/jekyll.yml` construit et publie le site à chaque push.
