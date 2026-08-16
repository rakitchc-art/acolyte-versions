# Acolyte — les versions

**Depuis ton téléphone, tu retrouves toutes tes conversations Claude Code qui tournent sur ton
PC.** Tu lis le fil, tu écris, et le travail continue là-bas — sur tes vrais fichiers, même
écran verrouillé.

👉 **[Télécharger la dernière version](../../releases/latest)**

Un seul fichier. Télécharge `Acolyte.exe`, double-clique dessus : il vérifie ce qu'il faut, te
demande un mot de passe, et t'affiche un code à scanner avec ton téléphone. Rien à installer
avant.

---

## Ce dépôt ne contient que les versions publiées

Le code source vit ailleurs, dans un dépôt privé. Ici, il n'y a que les exécutables et leurs
notes — c'est ce qui permet à Acolyte d'aller chercher lui-même sa mise à jour, sans qu'aucune
clé d'accès n'ait à voyager dans le programme distribué.

## Ce qu'il te faut sur ton PC

| Quoi | Pourquoi |
|---|---|
| **Claude Code** | Acolyte le *pilote*, il ne le remplace pas. C'est le Claude Code installé sur ta machine qui travaille, sur tes vrais fichiers. |
| **Tailscale** | Il donne à ton PC une adresse privée que seul ton téléphone atteint. Aucun serveur, rien à héberger, rien à payer. |

L'installateur vérifie les deux et te guide si l'un manque. Il n'installe ni ne modifie rien à
ta place.

## Où vont tes données

Nulle part. Acolyte n'écoute que sur ton propre PC (`127.0.0.1`) ; c'est Tailscale, ton réseau
privé, qui porte la liaison jusqu'à ton téléphone. Ton mot de passe est stocké haché, jamais en
clair, et Acolyte ne l'invente pas — c'est toi qui le choisis.

## Mettre à jour

Clic droit sur l'icône près de l'horloge → **Mettre à jour…**. Acolyte va chercher ici s'il
existe mieux, te le dit, et ne fait rien sans ton accord. Jamais pendant qu'une conversation
travaille.

---

*Windows affichera un avertissement au premier lancement : ce programme n'est pas encore signé.*
