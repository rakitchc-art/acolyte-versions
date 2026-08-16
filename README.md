<h1 align="center">Acolyte</h1>

<p align="center">
  <b>Depuis ton téléphone, tu retrouves toutes tes conversations Claude Code qui tournent sur ton PC.</b><br>
  Tu lis le fil, tu écris, et le travail continue là-bas — sur tes vrais fichiers, même écran verrouillé.
</p>

<p align="center">
  <a href="https://github.com/rakitchc-art/acolyte-versions/releases/latest/download/Acolyte.exe">
    <img alt="Télécharger Acolyte pour Windows"
         src="https://img.shields.io/badge/⬇%20T%C3%A9l%C3%A9charger%20Acolyte-Windows%20·%20un%20seul%20fichier-1f6fd0?style=for-the-badge">
  </a>
</p>

<p align="center"><i>Ce lien donne toujours la dernière version. Rien à installer avant.</i></p>

---

## Installer, en trois gestes

1. **Télécharge** `Acolyte.exe` avec le bouton ci-dessus.
2. **Double-clique** dessus. Windows affichera *« Windows a protégé votre ordinateur »* :
   clique sur **Informations complémentaires**, puis **Exécuter quand même** — le programme
   n'est pas encore signé.
3. La fenêtre déroule ce qu'elle vérifie, te demande **un mot de passe**, et affiche un
   **code à scanner** avec ton téléphone. C'est fini.

Acolyte s'installe ensuite dans ton dossier personnel — jamais dans « Program Files », donc
aucune fenêtre d'autorisation — et il **démarre avec Windows**. Tu le retrouves près de
l'horloge, en bas à droite.

## Ce qu'il te faut déjà sur ce PC

| Quoi | Pourquoi | Où |
|---|---|---|
| **Claude Code** | Acolyte le *pilote*, il ne le remplace pas. C'est le Claude Code de ta machine qui travaille, sur tes vrais fichiers. | [L'installer](https://docs.claude.com/en/docs/claude-code/setup) |
| **Tailscale** | Il donne à ton PC une adresse privée que seul ton téléphone atteint. Aucun serveur, rien à héberger, rien à payer. | [L'installer](https://tailscale.com/download/windows) |

L'installateur vérifie les deux, te dit lequel manque, ouvre la bonne page et **revérifie tout
seul** pendant que tu t'en occupes. Il n'installe ni ne modifie rien à ta place.

## Ce qu'Acolyte sait faire

- Le **catalogue complet** de tes projets et conversations, cherchable
- Le fil qui s'écrit **en direct** : la réflexion, puis la réponse
- Envoi de messages et d'**images**, changement de modèle et d'effort
- Les **autorisations hors projet**, accordées ou refusées depuis le téléphone
- Ton PC **ne s'endort plus** tant qu'Acolyte tourne, et il répond **écran verrouillé**
- Une conversation **déjà ouverte sur le PC se refuse au téléphone**, avec sa raison
- Réseau coupé, PC éteint, Claude qui s'arrête : **l'écran le dit et se rattrape seul**

## Où vont tes données

**Nulle part.** Acolyte n'écoute que sur ton propre PC (`127.0.0.1`) ; c'est Tailscale, ton
réseau privé, qui porte la liaison jusqu'à ton téléphone. Ton mot de passe est stocké haché,
jamais en clair, et Acolyte ne l'invente pas — c'est toi qui le choisis.

## Mettre à jour

Clic droit sur l'icône près de l'horloge → **Mettre à jour…**. Acolyte vient voir ici s'il
existe mieux, te le dit, et ne fait rien sans ton accord. Jamais pendant qu'une conversation
travaille.

---

<sub>Ce dépôt ne contient que les versions publiées. Le code source vit dans un dépôt privé —
c'est ce qui permet à Acolyte d'aller chercher lui-même sa mise à jour sans qu'aucune clé
d'accès ne voyage dans le programme distribué.</sub>
