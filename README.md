# KLYX Discovery Form - Déploiement Vercel

## Fichiers prêts à déployer

- `index.html` - Formulaire discovery avec credentials Supabase configurés
- `vercel.json` - Configuration Vercel

## Option 1 : Déploiement via Dashboard Vercel (Recommandé)

1. Va sur https://vercel.com/new
2. Clique sur "Add New..." > "Project"
3. Glisse-dépose ce dossier (klyx-discovery) dans la zone de drop
4. Vercel va auto-détecter la config et déployer
5. Tu obtiendras une URL type `klyx-discovery-xxx.vercel.app`

## Option 2 : Déploiement via CLI

```bash
cd klyx-discovery
vercel login  # Si pas encore authentifié
vercel --prod
```

## Credentials Supabase

Déjà configurés dans index.html :
- URL: https://ctdavxbdxpfcnvwybpfr.supabase.co
- ANON_KEY: eyJhbGci... (dans le fichier)

## Post-déploiement

- Teste le formulaire sur l'URL Vercel
- Vérifie les réponses dans Supabase Dashboard
- Configure un domaine custom si besoin
