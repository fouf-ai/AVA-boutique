# AVA-boutique

Site statique de la marketplace AVA.ME.

Déploiement sur Vercel

Option A — via GitHub (recommandé):
1. Sur https://vercel.com, connecte-toi et choisis "Import Project" → GitHub.
2. Sélectionne le dépôt `fouf-ai/AVA-boutique` et importe.
3. Vercel détecte le projet statique; les réglages par défaut conviennent. Déployer.

Option B — via CLI:
```bash
npm i -g vercel
vercel login
vercel # suivre les instructions (ou `vercel --prod` pour production)
```

Notes:
- `vercel.json` force l'utilisation d'`index.html` pour toutes les routes (SPA).
- Le dépôt est prêt; j'ai ajouté `vercel.json` et poussé les modifications sur `main`.

Si tu veux, je peux créer un projet Vercel et le connecter automatiquement (j'aurai besoin d'un token Vercel que tu dois fournir dans ton compte — je ne peux pas le saisir pour toi).