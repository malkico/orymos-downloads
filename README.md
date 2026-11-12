# Téléchargements Orymos

Ce dépôt distribue les installateurs Windows du Runner Orymos via les releases GitHub.

## Téléchargement recommandé pour Windows

[Télécharger Orymos Runner 0.1.1](https://github.com/malkico/orymos-downloads/releases/download/runner-5d867f4c703410ac6b5023e246976634de935239-43269917395/Orymos-Runner-Setup-0.1.1.exe)

Build `5d867f4` · Installateur non signé  
SHA-256 `c5c3d8a45b06de5ef3723e6396b757526a5b704ce2ac65c4eb0599bc522106f6`

Dans PowerShell, depuis le dossier de téléchargement, exécutez la commande suivante et comparez l’empreinte affichée à celle ci-dessus.

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath '.\Orymos-Runner-Setup-0.1.1.exe'
```

Un compte Orymos et un appairage sont nécessaires pour utiliser le service.

Le code source de l'application et les images Docker ne sont pas publiés ici.
