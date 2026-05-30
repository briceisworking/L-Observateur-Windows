# L'Observateur Windows

# EXERCICE 1

Les principaux types de journaux sont : 
- Applications
- Sécurité
- Installation
- Système
- Evénements transférés

Il y a aussi les journaux des applications et des services ( OpenSSH , service de gestion de clés etc.. )

# EXERCICE 2

- Création du filtre
![FILTRE_OBS_WIN](FILTRE_OBS_WIN.png)

- Analyse un événement d'information du journal Système : que te dit l'ID de l'événement ?
Dans ce cas l'ID 19 est un ID de WindowsUpdateClient qui indique une installation de mise à jour
![OBS_WIN_ID](OBS_WIN_ID.png)

# EXERCICE 3

J'ai pris en exemple l'ID numéro 14 : 
![OBS_WIN_ID_ERROR](OBS_WIN_ID_ERROR.png)

J'ai trouvé pas mal d'informations sur ce lien : https://learn.microsoft.com/fr-fr/troubleshoot/windows-client/windows-security/tpm-device-driver-error-log

