# AUREON AI
### Beyond Intelligence. — Your intelligence. Your empire.

AUREON AI est une plateforme d'intelligence artificielle personnelle à l'identité
visuelle luxueuse : noir obsidienne, or champagne, verre fumé et photographies
immersives (supercars, villas, jets privés, bureaux).

Chaque utilisateur se connecte avec sa propre clé API Groq. La clé est vérifiée
côté serveur, chiffrée dans un cookie httpOnly et n'est jamais stockée dans le
navigateur (pas de localStorage), ni dans une URL, ni dans les logs.

## Fonctionnalités actuelles (Phase 1)
- Écran de connexion en verre fumé avec vérification réelle de la clé Groq
- Chat en streaming avec choix du modèle parmi ceux disponibles sur la clé
- 7 personnalités IA : AUREON, ATLAS, NOVA, TITAN, SOVEREIGN, ORION, ELITE
- Déconnexion qui supprime la session
- Limitation des requêtes et messages d'erreur clairs (clé invalide, quota, réseau)

## À venir
Tableau de bord, historique des conversations, Studio d'écriture, Academy,
conjugaison, mathématiques, quiz, voix, mode concentration, mémoire,
carte de membre Black Card.

## Technologies
Next.js, React, TypeScript, API Groq. Déploiement : Vercel.

## Lancement
npm install && npm run dev
(Variable d'environnement requise en production : SESSION_SECRET, 32 caractères minimum.)
