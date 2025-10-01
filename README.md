# Signature e‑mail — Lucas Privat

Ce dossier est prêt pour GitHub Pages.

## Publication rapide (GitHub Pages — Branche `main`)

1. Crée un dépôt **public** nommé, par exemple, `signature-lucas`.
2. Envoie ces fichiers (`index.html` et `Lucas_Email_Header.png`) sur la branche `main` :
   - via l'interface GitHub (« Add file » → « Upload files »), ou
   - via Git :
     ```bash
     git init
     git add .
     git commit -m "Signature Lucas Privat"
     git branch -M main
     git remote add origin https://github.com/<ton-username>/signature-lucas.git
     git push -u origin main
     ```
3. Active GitHub Pages : **Settings → Pages → Build and deployment**
   - *Source* : `Deploy from a branch`
   - *Branch* : `main` / `/ (root)`
4. Ton site sera disponible sur `https://<ton-username>.github.io/signature-lucas/`
   - L'URL de l'image à utiliser dans ta signature e‑mail sera :
     `https://<ton-username>.github.io/signature-lucas/Lucas_Email_Header.png`

## Snippet HTML pour la signature (à coller dans iCloud/Gmail/Outlook web)

```html
<table role="presentation" cellpadding="0" cellspacing="0" border="0" style="border-collapse:collapse;width:600px;max-width:100%;">
  <tr>
    <td style="padding:0;margin:0;line-height:0;">
      <a href="mailto:lucas_privat@icloud.com" style="text-decoration:none;border:0;display:inline-block;">
        <img src="https://<ton-username>.github.io/signature-lucas/Lucas_Email_Header.png"
             width="600" alt="Lucas Privat — Chargé de communication | +33 6 48 81 50 04 | Nîmes / Montpellier"
             style="display:block;border:0;outline:none;text-decoration:none;width:600px;max-width:100%;height:auto;">
      </a>
    </td>
  </tr>
</table>
```
