# Maniart Sport — PWA pour iPad

## Publier depuis un iPad (GitHub Pages)
1. Dans Safari, connectez-vous à github.com et créez un dépôt public, par exemple `maniart-sport-demo`.
2. Dans le dépôt, choisissez **Add file > Upload files** et importez les fichiers de ce dossier **à la racine**, avec le dossier `icons`. Sur iPad, le mode « site pour ordinateur » de Safari peut être utile.
3. Ouvrez **Settings > Pages > Build and deployment** ; choisissez **Deploy from a branch**, branche `main`, dossier `/(root)` puis **Save**.
4. Après publication, ouvrez l'URL Pages fournie par GitHub en HTTPS dans Safari.
5. Dans Safari : **Partager > Sur l'écran d'accueil > Ajouter**.

Attention : un dépôt public expose le code et les tarifs de démonstration. Ne mettez aucun mot de passe ni donnée client dans ce dépôt.

## Fonctionnement
Cette PWA garde les informations dans le stockage local du navigateur. Le mode admin n'est **pas sécurisé**. Aucune donnée n'est partagée entre appareils. Aucun paiement ni réservation réelle n'est activé. N'y saisissez aucune donnée de santé ou personnelle réelle. L'utilisation hors connexion fonctionne après une première ouverture réussie en HTTPS, dans les limites du navigateur.

## Pour un déploiement professionnel
Ajouter Supabase Auth, règles RLS, base de données et contrôle serveur des réservations ; Stripe côté serveur ; politiques RGPD et gestion du consentement. Les tarifs et créneaux sont fictifs et doivent être validés.
