# gql


Générez instantanément des types TypeScript type-safe et toutes vos opérations GraphQL (queries & mutations) à partir d’un simple fichier `schema.graphql` — fini les décalages entre backend et frontend !


## Aperçu

Ce projet génère les types TypeScript et des opérations GraphQL basées sur un fichier de schéma GraphQL (`schema.graphql`).

## Configuration du schéma

Le schéma GraphQL peut être fourni de deux manières :

1. **Fichier local** : Placez votre fichier `schema.graphql` dans le répertoire `src/`
2. **Téléchargement distant** : Utilisez la commande suivante pour télécharger le schéma depuis une URL :

```bash
npm run dl
```

## Utilisation

Après avoir configuré votre schéma, exécutez la commande ```bash npm run build``` pour générer les types TypeScript et les opérations pour vos requêtes et mutations GraphQL.

## Structure du projet

```
src/
├── schema.graphql    # Votre fichier de schéma GraphQL
└── ...               # Types et opérations générés
```
