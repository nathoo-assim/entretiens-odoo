# Entretiens Odoo

Questionnaires d'entretien de cadrage pour des projets Odoo Community, publiés par GitHub
Pages. Chaque questionnaire est une page autonome, sans dépendance : on saisit les réponses
à l'écran, elles s'enregistrent dans le navigateur de l'appareil, puis on les exporte.

## Questionnaires

| Dossier | Secteur | Adresse |
|---|---|---|
| `usine-matelas/` | Usine de matelas en mousse | https://nathoo-assim.github.io/entretiens-odoo/usine-matelas/ |

## Règles

- **Générique** : aucun nom de client, de marque ni de donnée propre à une entreprise. Ce
  dépôt est public.
- **Aucune réponse ici** : les réponses restent dans le navigateur qui les saisit et ne
  quittent l'appareil que par un export. Ne jamais déposer un export dans ce dépôt.
- La page empêche son indexation par les moteurs de recherche (`noindex`), ce qui n'est pas
  une protection : son contenu reste lisible par tous.

## Fonctionnement d'une page

- Sauvegarde automatique dans le navigateur (`localStorage`), à chaque frappe.
- Export du compte rendu (Markdown), copie, partage sur téléphone, impression.
- Fichier de sauvegarde JSON, réimportable sur un autre appareil.
- Changer une question : modifier le tableau `SECTIONS` du script de la page, et monter la
  clé de stockage (`CLE`) si la structure change.
