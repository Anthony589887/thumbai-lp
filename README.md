# Guide — Modifier la landing page ThumbAI

## Le projet

La landing page ThumbAI est hébergée sur Vercel et le code source est sur GitHub.

- **Site en ligne** → https://thumbai-lp.vercel.app
- **Repo GitHub** → https://github.com/Anthony589887/thumbai-lp

Le projet contient deux fichiers :
- `index.html` — la landing page principale
- `pricing.html` — la page pricing

---

## Accès au repo

Anthony t'enverra une invitation GitHub à ton adresse email.
Accepte l'invitation, puis clone le repo sur ton Mac :

```bash
git clone https://github.com/Anthony589887/thumbai-lp.git
cd thumbai-lp
```

---

## Faire une modification

**1. Ouvre le fichier dans ton éditeur** (VS Code, Cursor, etc.)

```bash
code index.html
```

**2. Fais tes modifications** directement dans le HTML/CSS

**3. Sauvegarde et pousse sur GitHub**

```bash
git add .
git commit -m "description de ta modification"
git push
```

**4. Vercel redéploie automatiquement** en 20-30 secondes.
Tu peux suivre le déploiement sur https://vercel.com

---

## Structure du code

Tout est dans un seul fichier HTML par page.
Le CSS est dans la balise `<style>` en haut du fichier.
Le JavaScript est dans la balise `<script>` en bas du fichier.

Les variables de couleurs et polices sont définies en haut du CSS :

```css
:root {
  --bg: #0A0A0A;          /* fond principal */
  --orange: #FF5C00;      /* couleur brand */
  --text: #F5F5F5;        /* texte principal */
  --text-2: #A0A0A0;      /* texte secondaire */
  --font-display: 'SF Pro Display', -apple-system, sans-serif;
  --font-body: 'DM Sans', sans-serif;
  --font-mono: 'DM Mono', monospace;
}
```

---

## Récupérer les dernières modifications d'Anthony

Avant de commencer à travailler, toujours récupérer la dernière version :

```bash
git pull
```

---

## En cas de problème

Contacte Anthony directement.
