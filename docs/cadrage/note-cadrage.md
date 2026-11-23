# Note de Cadrage : Blog des Lauréats

> **Projet :** Blog des Lauréats (EFP) | **Phase :** Sprint 0 | **Livrable :** Note de cadrage synthétique

---

## 1. Contexte & Mission Institutionnelle

- **Contexte EFP :** Absence d'espace centralisé pour capitaliser et partager les retours d'expérience des anciens stagiaires avec les apprenants actuels.
- **Mission :** Déployer une plateforme institutionnelle pour valoriser les réussites des lauréats et guider les apprenants dans leur insertion.

---

## 2. Objectifs SMART

- **Spécifique (S) :** Plateforme web pour rédiger, modérer et consulter des articles professionnels de lauréats.
- **Mesurable (M) :**
  - $\ge$ 15 articles de référence publiés au lancement.
  - Temps de chargement < 500 ms.
  - Interface 100% responsive (mobile, tablette, desktop).
- **Atteignable (A) :** 2 sprints Scrum courts (80h/sprint) avec tranches fonctionnelles testées de bout en bout.
- **Réaliste (R) :** Stack maîtrisée : **Laravel, MySQL, Blade, Tailwind CSS, Alpine.js**.
- **Temporel (T) :**
  - **Sprint 0 :** Cadrage, maquettage et socle technique.
  - **Sprint 1 :** Authentification, CRUD articles et espace de modération.

---

## 3. Matrice de Périmètre (MVP)

| In-Scope (Inclus) | Out-of-Scope (Exclu) |
| :--- | :--- |
| Consultation des articles par catégorie | Messagerie instantanée en direct (Live chat) |
| Recherche textuelle d'articles | Paiement et monétisation en ligne |
| Espace d'administration & modération | Réseau social complexe (followers, feed algorithmique) |
| Authentification sécurisée | Application mobile native (iOS / Android) |
| Gestion des statuts (*Brouillon*, *En attente*, *Publié*, *Rejeté*) | |
| Profils des lauréats (bio, parcours, liens pro) | |

---

## 4. Parties Prenantes

- **Product Owner (Groupe 1) :** Définition de la vision produit et validation des livrables de sprint.
- **Développeurs :** Conception technique, développement, tests et intégration.
- **Formateurs Référents (Lead Trainers) :** Encadrement méthodologique, revues de code et validation d'architecture.
- **Visiteurs Publics & Apprenants :** Consultation des contenus, recherche et exploitation des retours d'expérience.

---

## 5. Risques & Stratégies d'Atténuation

| Risque Identifié | Impact | Stratégie d'Atténuation |
| :--- | :---: | :--- |
| **Disponibilité du contenu** (Retard de rédaction des lauréats) | Élevé | Fourniture de templates d'articles et injection de données témoins (*seeders*) dès le Sprint 0. |
| **Respect des délais de sprint** (Dépassement du planning Scrum) | Élevé | Découpage en User Stories indépendantes, priorisation MoSCoW (*Must Have*) et Daily Stand-ups. |

---

## 6. Contraintes d'Accessibilité & Ergonomie

- **Contraste visuel :** Respect strict des règles de contraste (normes WCAG niveau AA).
- **Mobile-first :** Ergonomie assurant une lisibilité et navigation exemplaires sur smartphones.
- **Sémantique :** Balisage HTML5 sémantique garantissant le bon fonctionnement des lecteurs d'écran.


---