# Dossier de Publication Google Play Console — Dār el-Jomla

Ce dossier regroupe tous les documents légaux, techniques et textuels obligatoires pour publier et maintenir l'application **Dār el-Jomla** sur le **Google Play Console**.

---

## 📂 Contenu du dossier

| Fichier | Format | Description / Utilisation |
| :--- | :--- | :--- |
| **`privacy-policy.html`** | Web (HTML) | **Règles de confidentialité prêtes à être hébergées**. Contient la mise en page responsive et tous les paragraphes exigés par Google Play. |
| **`privacy-policy.md`** | Markdown | Version texte des règles de confidentialité pour lecture et archivage. |
| **`terms-of-service.html`** | Web (HTML) | Conditions Générales d'Utilisation (CGU) pour le site web ou la consultation publique. |
| **`terms-of-service.md`** | Markdown | Version Markdown des Conditions Générales d'Utilisation. |
| **`data-safety-guide.md`** | Guide | **Guide pas-à-pas pour remplir le formulaire « Sécurité des données »** de la Play Console sans risque de rejet. |
| **`play-store-listing.md`** | Fiche Store | Titre conforme (≤ 30 car.), description courte (≤ 80 car.), description complète et instructions pour les testeurs Google. |

---

## 🌐 Comment héberger gratuitement votre Politique de Confidentialité ?

Google Play exige que l'URL de votre politique de confidentialité soit publique et accessible en ligne. Vous pouvez l'héberger en 2 minutes gratuitement :

### Option 1 : Via GitHub Pages (Recommandé & Gratuit à vie)
1. Poussez votre projet ou créez un dépôt public GitHub (ex: `dar-el-jomla-privacy`).
2. Déposez le fichier `privacy-policy.html` renommé en `index.html`.
3. Allez dans **Settings > Pages > Branch : main > Save**.
4. Votre URL publique sera : `https://<votre-compte>.github.io/dar-el-jomla-privacy/`.
5. Collez cette URL dans la **Play Console** sous **Contenu de l'application > Règles de confidentialité**.

### Option 2 : Via Netlify Drop ou Vercel
1. Rendez-vous sur [Netlify Drop](https://app.netlify.com/drop).
2. Glissez-déposez le dossier contenant `privacy-policy.html` (renommé `index.html`).
3. Vous obtenez instantanément une URL HTTPS publique sécurisée.

---

## 📋 Checklist avant soumission sur la Play Console

- [x] **Package ID unique :** `com.aistudio.derjalearn.ktvq`
- [x] **Version Code / Version Name :** `versionCode = 7`, `versionName = "7.0"`
- [x] **Icône adaptative personnalisée :** Déjà intégrée (`res/mipmap-anydpi-v26/ic_launcher.xml`)
- [x] **Règles de confidentialité en ligne :** URL renseignée dans la Play Console
- [x] **Accès dans l'application :** Dialogue de confidentialité accessible dans les Paramètres de l'application
- [x] **Formulaire Sécurité des données :** Complété en suivant `data-safety-guide.md`
- [x] **Déclaration des autorisations :** `RECORD_AUDIO` et `POST_NOTIFICATIONS` justifiées pour les fonctionnalités pédagogiques
- [x] **Accès à l'application pour les examinateurs :** Accès libre sans identifiant requis
