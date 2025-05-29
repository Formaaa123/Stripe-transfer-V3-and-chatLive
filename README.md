# Stripe-transfer-V3-and-chatLive

## ⚡️ Setup Instructions

### 🇬🇧 English

1️⃣ **Install Crocoblock and JetEngine**  
Download and install the latest versions of [Crocoblock](https://crocoblock.com/) and [JetEngine](https://crocoblock.com/plugins/jetengine/) plugins in your WordPress site.

2️⃣ **Install the Stripe library**  
Download the official [Stripe PHP library](https://github.com/stripe/stripe-php) and place it at the root of your child theme directory.

3️⃣ **Update your tokens in `wp-config.php`**  
Edit your `wp-config.php` file and add (or update) your Stripe API secret tokens as environment variables.

---

### 🇫🇷 Français

1️⃣ **Installer Crocoblock et JetEngine**  
Téléchargez et installez les dernières versions des plugins [Crocoblock](https://crocoblock.com/) et [JetEngine](https://crocoblock.com/plugins/jetengine/) sur votre site WordPress.

2️⃣ **Installer la librairie Stripe**  
Téléchargez la [librairie Stripe PHP officielle](https://github.com/stripe/stripe-php) et placez-la à la racine du dossier de votre thème enfant.

3️⃣ **Modifier vos tokens dans `wp-config.php`**  
Éditez le fichier `wp-config.php` et ajoutez (ou mettez à jour) vos tokens secrets Stripe comme variables d’environnement.

---

## ✅ Features / Fonctionnalités

<details>
<summary><strong>🇬🇧 English</strong></summary>

- ✅ Chat: automatic user registration when opening the chat window
- ✅ Chat: prevents user disconnection for 5 minutes
- ✅ Chat: real-time messaging
- ✅ Chat: unique user creation and verification if user already exists
- ✅ Chat: role assignment based on WordPress accounts
- ✅ Chat: automatic message sent when a new order is confirmed
- ✅ Chat: automatic message sent to moderator when an order is cancelled
- ✅ Stripe: creation of a seller profile linked to the WordPress project
- ✅ Stripe: card payment integration
- ✅ Stripe: manual or instant (automatic) payment validation according to specific conditions
- ✅ Stripe: redirect to thank-you page 5 seconds after successful payment
- ✅ Stripe: automatic seller detection when an order is placed
- ✅ Stripe: three transfers management (platform/seller/VAT)
- ✅ Stripe: management of an additional commercial tax (3%) with conditional rules depending on the contract
- ✅ WooCommerce: order status management on payment validation without payment errors
- ✅ Security: API secret token protection for Stripe and Chat (no public access)
- ✅ Form: multi-step confirmation form management
- ✅ Hosting: payment-related files stored securely on a remote server (not publicly accessible)
- ✅ Order Recap: full order summary in Stripe (product reference, purchase date, delivery date, WooCommerce invoice, amount, and origin)

</details>

<details>
<summary><strong>🇫🇷 Français</strong></summary>

- ✅ Chat inscription quand ouverture de messagerie côté utilisateur
- ✅ Chat anti-déconnexion pendant 5 minutes
- ✅ Chat en temps réel
- ✅ Chat création d'un user unique et vérification de l'existence
- ✅ Chat répartition des rôles selon les comptes WordPress
- ✅ Chat message automatique lors d'une nouvelle commande confirmée
- ✅ Chat message automatique envoyé au modérateur lors d'une commande annulée
- ✅ Stripe création d'un profil vendeur relié au projet WordPress
- ✅ Stripe paiement par carte bancaire
- ✅ Stripe validation manuelle ou automatique (paiement instantané) selon conditions spécifiques
- ✅ Redirection après paiement vers la page de remerciement (après 5 secondes)
- ✅ Détection automatique du vendeur à l'enregistrement d'une commande
- ✅ 3 transferts Stripe gérés (plateforme/vendeur/TVA)
- ✅ Gestion d'une taxe commerciale supplémentaire (3 %) et règles conditionnelles selon le contrat
- ✅ Gestion des statuts WooCommerce à la validation du paiement sans erreurs
- ✅ Sécurisation des tokens secrets des API Stripe et Chat (aucun accès public)
- ✅ Gestion d'un formulaire avec étape de confirmation
- ✅ Fichiers de paiement stockés de façon sécurisée sur un serveur distant (inaccessibles au public)
- ✅ Récapitulatif de la commande sur Stripe (réf. produit, date d'achat, date de livraison, facture WooCommerce, montant et provenance)

</details>

---

## ℹ️ Notes

- Please adapt installation steps to your specific project structure if needed.
- For any issues or to request additional features, please open an issue on GitHub.
