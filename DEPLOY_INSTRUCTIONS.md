# 🚀 Istruzioni per Deploy su GitHub e Vercel

## ✅ Repository Git Creato
Il repository Git locale è stato inizializzato con successo nella directory:
`/Users/wrdigital/.gemini/antigravity/scratch/b2vibe-coming-soon`

## 📋 Prossimi Passi

### 1. Crea un nuovo repository su GitHub

1. Vai su https://github.com/new
2. Nome repository: `b2vibe-coming-soon`
3. Descrizione: `B2Vibe - Pagina temporanea in lavorazione`
4. Visibilità: **Public** (o Private se preferisci)
5. **NON** selezionare "Add a README file" (già presente)
6. Clicca su **"Create repository"**

### 2. Collega il repository locale a GitHub

Nel terminale, esegui questi comandi (sostituisci `TUO-USERNAME` con il tuo username GitHub):

```bash
cd /Users/wrdigital/.gemini/antigravity/scratch/b2vibe-coming-soon

# Aggiungi il remote (sostituisci TUO-USERNAME)
git remote add origin https://github.com/TUO-USERNAME/b2vibe-coming-soon.git

# Push del codice
git branch -M main
git push -u origin main
```

### 3. Deploy su Vercel

1. Vai su https://vercel.com/new
2. Clicca su **"Import Git Repository"**
3. Seleziona il repository `b2vibe-coming-soon`
4. Vercel rileverà automaticamente che è un sito statico
5. Clicca su **"Deploy"**
6. Attendi qualche secondo... e il sito sarà online! 🎉

### 4. (Opzionale) Configura il dominio personalizzato

Dopo il deploy, puoi configurare un dominio personalizzato:
1. Vai nelle impostazioni del progetto su Vercel
2. Sezione "Domains"
3. Aggiungi il tuo dominio (es. `coming.b2vibe.com`)
4. Segui le istruzioni per configurare il DNS

---

## 📁 File nel Repository

- `index.html` - Pagina principale
- `style.css` - Stili CSS
- `script.js` - JavaScript minimo
- `logo.png` - Logo B2Vibe
- `README.md` - Documentazione
- `.gitignore` - File da ignorare

---

## ✨ Il sito è pronto!

Una volta deployato su Vercel, il sito sarà accessibile all'indirizzo:
`https://b2vibe-coming-soon.vercel.app` (o un nome simile)

Puoi poi configurare un dominio personalizzato come preferisci.
