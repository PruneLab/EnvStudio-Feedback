# EnvStudio Feedback

<p align="right">
  <a href="README.md">English (US)</a>
  |
  <a href="README.zh-Hans.md">简体中文</a>
  |
  <a href="README.zh-Hant.md">繁體中文</a>
  |
  <a href="README.ja.md">日本語</a>
  |
  <a href="README.de.md">Deutsch</a>
  |
  <a href="README.es.md">Español</a>
  |
  <a href="README.pt.md">Português</a>
  |
  <a href="README.ru.md">Русский</a>
  |
  <a href="README.ko.md">한국어</a>
</p>

## À propos d'EnvStudio

**EnvStudio** est un gestionnaire moderne de variables d'environnement Windows basé sur WinUI 3. Il remplace le vieux dialogue « Propriétés système → Variables d'environnement » par une expérience native Windows 11.

<p align="center">
  <img src="https://prunelab.net/products/envstudio/covers/fr/cover1.png" width="48%" />
  <img src="https://prunelab.net/products/envstudio/covers/fr/cover2.png" width="48%" />
</p>

## Télécharger

<p>
  <a href="https://apps.microsoft.com/detail/9nl5scxw3320" target="_blank">
    <img src="https://get.microsoft.com/images/en-us%20dark.svg" width="200" alt="Download from Microsoft Store"/>
  </a>
</p>

## Fonctionnalités principales

- **Éditeur visuel intuitif** — Ajoutez, modifiez, supprimez et réorganisez les variables d'environnement avec une interface WinUI 3 moderne.
- **Gestion de la liste PATH** — Réorganisation par glisser-déposer, détection des doublons et des liens cassés.
- **Détection des conflits EXE** — Scanne tous les répertoires du PATH pour les exécutables et montre lesquels sont écrasés par des entrées précédentes, avec accès direct à l'entrée en conflit.
- **Détection des conflits de portée** — Lorsqu'une variable utilisateur masque une variable système du même nom, affiche un barré avec une icône d'avertissement pour toujours savoir quelle valeur est réellement en vigueur.
- **Basculement non destructif** — Désactivez une variable sans la supprimer. Renomme silencieusement la valeur de registre en préservant les données d'origine. Réactivez à tout moment en un clic.
- **Vérifications de sécurité avant suppression** — Avant de supprimer une variable, scanne toutes les autres variables pour les références `%VARNAME%` et avertit des cassures potentielles.
- **Aperçu de l'expansion des variables** — Survolez toute valeur contenant des références `%VAR%` pour voir le chemin entièrement résolu dans une info-bulle.
- **Détection des changements externes** — Surveille le registre en temps réel. Si un autre programme modifie les variables d'environnement en votre absence, vous recevez une notification immédiate.
- **Système de profils** — Enregistrez, changez et appliquez des profils de variables pour différents environnements de développement (ex. « Java 8 », « Node.js », « AI/ML »).
- **Snapshot et restauration** — Snapshots automatiques avant chaque modification, avec vue diff style Git et restauration en un clic.
- **Recherche et filtrage** — Trouvez rapidement des variables entre les portées Utilisateur et Système avec support regex. Les sous-entrées PATH correspondantes sont automatiquement développées avec un badge.
- **Export** — Exportez les variables aux formats PowerShell, Batch ou fichier .env pour le partage en équipe ou la récupération système.
- **Élévation UAC** — Élévation administrateur transparente pour modifier les variables système.
- **Diffusion instantanée** — Les modifications sont immédiatement diffusées au système via `WM_SETTINGCHANGE`.

## 100% Hors ligne · Entièrement gratuit

EnvStudio fonctionne **entièrement hors ligne, sans télémétrie ni collecte de données.** Votre configuration reste strictement sur votre propre machine.

Toutes les fonctionnalités sont **entièrement gratuites**, sans publicité ni paywall. Une option de don pourra être ajoutée à l'avenir, mais aucune fonctionnalité ne sera jamais restreinte.

Consultez notre [Politique de confidentialité](https://prunelab.net/fr/products/envstudio/privacy) pour plus de détails.

---

## Feedback

> **Remarque :** Ce dépôt ne **contient pas** le code source d'EnvStudio. Il est dédié au recueil des retours utilisateurs et au suivi des problèmes.

| Action | Lien |
|------|------|
| Signaler un bug | [Créer un rapport de bug](https://github.com/PruneLab/EnvStudio-Feedback/issues/new?template=bug_report.yml) |
| Suggérer une fonctionnalité | [Soumettre une demande](https://github.com/PruneLab/EnvStudio-Feedback/issues/new?template=feature_request.yml) |
| Voir tous les Issues | [Issues](https://github.com/PruneLab/EnvStudio-Feedback/issues) |

## Avant de signaler

Veuillez d'abord consulter les [Issues existants](https://github.com/PruneLab/EnvStudio-Feedback/issues) pour éviter les doublons.

Lors du signalement d'un bug, veuillez inclure :
- **Version d'EnvStudio** (dans Paramètres → À propos)
- **Version de Windows** (ex. Windows 11 23H2)
- **Étapes pour reproduire** le problème
- **Comportement attendu** vs **comportement réel**
- Captures d'écran (si applicable)

## Idées de fonctionnalités

Nous adorons vos idées ! Avant de soumettre :
- Vérifiez si quelqu'un l'a déjà suggérée
- Décrivez le cas d'usage — quel problème cela résoudrait-il ?
- Les maquettes et références sont toujours les bienvenues
