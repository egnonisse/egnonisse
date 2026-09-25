# Bonjour, je suis Ouattara Anzoumana 👋

**Je construis des produits qui tournent en production, pas des prototypes.**

Développeur basé à **Abidjan (Côte d'Ivoire)**, je conçois et j'exploite des systèmes
complets : backend, applications mobiles, automatisation et IA appliquée. Mes projets sont
utilisés par de vrais utilisateurs et traitent de vraies commandes.

---

## 🚀 Projets

### 📱 PharmaScan — santé du quotidien
Application **Flutter** qui répond à deux besoins concrets en Côte d'Ivoire :
- **pharmacies de garde** à jour, consultables **hors ligne**
- **comparateur de prix** des médicaments, alimenté par les reçus scannés par la communauté

*Ce que ça démontre :* OCR on-device (ML Kit), architecture Firebase (Firestore,
Cloud Functions, FCM), mode hors ligne, publication Google Play.

### 💬 BotWhatsApp — vente conversationnelle
Bot **WhatsApp** connecté à l'API WhatsApp Cloud, qui vend réellement : il qualifie le
besoin, recommande des produits d'un catalogue de **~1 900 références** (WooCommerce),
gère les objections et crée la commande.

*Ce que ça démontre :* Python / FastAPI, intégration LLM avec **garde-fous
anti-hallucination** (vérification des prix, liens et noms par le code, pas par le modèle),
synchronisation de catalogue, supervision humaine via dashboard, déploiement VPS + systemd.

### 🏬 SellerCenter — marketplace multi-vendeurs
Plateforme type place de marché : gestion des vendeurs, contrôle qualité des fiches,
**commissions configurables** par catégorie, génération de relevés financiers.

*Ce que ça démontre :* Next.js, Prisma, PostgreSQL, authentification **RBAC** (4 rôles,
permissions par ressource), webhooks signés, tâches planifiées.

### ⌚ Aiwatch — e-commerce (aiwatch.ci)
Boutique en ligne complète : catalogue, SEO, automatisation email et réseaux sociaux,
extensions WordPress sur mesure.

---

## 🛠 Stack

**Langages** — Python · Dart/Flutter · TypeScript · PHP · SQL
**Backend** — FastAPI · Node.js · Next.js · Prisma · PostgreSQL · SQLite · Firebase
**Mobile** — Flutter (Android, iOS)
**Intégrations** — WhatsApp Cloud API · WooCommerce · Google APIs · Sentry · Vercel
**Pratiques** — tests, Conventional Commits, CI/CD (GitHub Actions), déploiement VPS/Linux

---

## 🎯 Comment je travaille

- **Production d'abord.** Ce qui compte est ce qui tourne chez l'utilisateur, pas la
  démo. Chaque projet ici est déployé et exploité.
- **Les garde-fous au niveau du code.** Quand un LLM peut se tromper, je ne lui fais pas
  confiance : je vérifie sa sortie par le code (prix, liens, identifiants).
- **Adapté au terrain.** Connexions instables, mobile-first, coûts maîtrisés : mes
  solutions sont pensées pour le contexte ivoirien et ouest-africain.

---

## 📬 Me contacter

- **Site** : [softhubapp.com](https://softhubapp.com)
- **GitHub** : [github.com/egnonisse](https://github.com/egnonisse)

---

<sub>🇬🇧 **English** — I build systems that run in production, not prototypes. Based in
Abidjan (Côte d'Ivoire), I work across Python/FastAPI, Flutter, Next.js and applied AI:
a Flutter health app (on-duty pharmacies + medicine price comparison), a conversational
WhatsApp sales bot with LLM guardrails, and a multi-vendor marketplace. Open to freelance
work and remote opportunities.</sub>
