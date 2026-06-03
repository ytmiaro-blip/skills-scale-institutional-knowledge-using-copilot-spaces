# OctoAcme — Project Management Process Docs (README)

Bienvenue ! Ce répertoire centralise la documentation sur les processus de gestion de projet utilisés par l'équipe OctoAcme. Il sert de point d'entrée unique pour découvrir nos pratiques, artefacts et rôles afin d'assurer une exécution cohérente et reproductible.

OctoAcme suit une approche itérative et incrémentale : chaque initiative démarre par une initiation (one‑pager, parties prenantes, jalons, risques) puis passe en planification où le travail est découpé en incréments livrables, priorisés et estimés. L'exécution s'appuie sur des rituels réguliers (standups quotidiens, revues/démos de sprint, syncs hebdomadaires) et sur un board de suivi (Backlog → Ready → In Progress → In Review → QA → Done). Les Pull Requests doivent rester petites, inclure un lien vers l'issue et les critères d'acceptation, et passer la CI avant demande de revue.

Les rôles sont explicitement définis pour garantir responsabilité et coordination : Product Manager (vision, priorisation, métriques), Project Manager (planification, risques, communications), Développeurs (implémentation, tests, revues) et QA (validation). La communication est standardisée (mises à jour hebdomadaires, templates de statut) et le registre des risques centralise impact, probabilité, propriétaire et actions de mitigation. L’assurance qualité combine tests unitaires, tests d’intégration, smoke tests E2E, scans sécurité en CI et QA manuelle au besoin.

Les rétrospectives et l’amélioration continue transforment les apprentissages en actions traçables intégrées au backlog. Avant chaque release, les exigences pré‑release (PRs fusionnées, CI & scans verts, notes de release, plan de rollback, smoke tests) doivent être satisfaites pour réduire les risques en production.

## Documents disponibles
- [Aperçu de la gestion de projet OctoAcme](./octoacme-project-management-overview.md)
- [Guide d'initiation de projet](./octoacme-project-initiation.md)
- [Guide de planification de projet](./octoacme-project-planning.md)
- [Exécution & suivi](./octoacme-execution-and-tracking.md)
- [Gestion des risques et communication](./octoacme-risks-and-communication.md)
- [Release et déploiement](./octoacme-release-and-deployment.md)
- [Rétrospective et amélioration continue](./octoacme-retrospective-and-continuous-improvement.md)
- [Rôles & personas](./octoacme-roles-and-personas.md)

## Acceptance Criteria
- [ ] Le contenu est aligné avec les documents existants dans docs/
- [ ] Le README facilite l’onboarding et sert de point d’entrée clair
- [ ] Le README est ajouté dans docs/ et disponible via une Pull Request
