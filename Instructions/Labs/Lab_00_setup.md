# Suite de l’utilisation d’exemples de données avec Microsoft 365 Copilot

Tout au long de ces labos, nous allons créer des prompts Microsoft 365 Copilot qui font référence aux fichiers suivants :

- [Promotion Plan for Chai Tea in Latin America.docx](https://go.microsoft.com/fwlink/?linkid=2269126)
- [Market Analysis Report for Mystic Spice Premium Chai Tea.docx](https://go.microsoft.com/fwlink/?linkid=2268826)
- [Contoso Chai Tea market trends 2023.xlsx](https://go.microsoft.com/fwlink/?linkid=2268822)

Pour vous assurer que ces fichiers sont accessibles ultérieurement par Microsoft 365 Copilot, nous les chargerons d’abord sur OneDrive.

## Chargement des fichiers dans OneDrive

Suivez les étapes ci-dessous pour charger tous les fichiers requis dans **OneDrive** :

1. Connectez-vous à la machine virtuelle fournie par votre fournisseur de locataire en tant que compte **Administrateur** local avec le mot de passe `Pa55w.rd`.

2. Ouvrez l’application **OneDrive** en entrant **OneDrive** dans la barre de recherche Windows.

3. À l’invite **Adresse e-mail**, saisissez userx@yourtenant.onmicrosoft.com(fournie par votre fournisseur de client) et sélectionnez **Se connecter**

4. Dans l’écran **Entrer le mot de passe**, saisissez Mot de passe 1 (fourni par votre fournisseur de locataire), puis sélectionnez **Se connecter**.

5. Si une invite **Se connecter automatiquement à toutes les applications de bureau et à tous les sites web sur cet appareil ?** s’affiche, sélectionner **Oui, toutes les applications**

6. Ouvrir votre dossier OneDrive
   
7. Dans une nouvelle fenêtre de **l’Explorateur de fichiers**, sélectionner **Ce PC** > **Disque local (C:)** et ouvrir le dossier **ResourceFiles**

8. Sélectionnez tous les fichiers du dossier **ResourceFiles**, puis les faire glisser vers votre dossier OneDrive

9. Une fois le chargement terminé, vous devriez voir **29 éléments chargés dans Mes fichiers** en bas au centre de l’écran.


### Référencement de fichiers

Lorsque vous référencez des fichiers à partir de Copilot, vous pouvez constater que vous ne pouvez pas trouver certains fichiers à partir des suggestions fournies. En effet, certaines expériences avec Copilot référencent uniquement les fichiers figurant dans la liste des éléments utilisés récemment, tandis que d’autres vous permettent de parcourir OneDrive pour trouver votre fichier. Il est aussi facile de les ajouter à cette liste que de les ouvrir dans l’application Microsoft 365 appropriée.  Une fois qu’ils ont été ouverts, ils doivent apparaître dans la liste des éléments utilisés récemment.

> [!IMPORTANT]
> Microsoft 365 Copilot fonctionne uniquement avec les fichiers enregistrés dans OneDrive. Si les fichiers sont stockés localement sur votre PC, vous devrez les déplacer vers OneDrive pour activer Copilot.

À mesure que vous progressez, vous aurez la possibilité d’essayer d’autres prompts sur ces fichiers et vous êtes encouragés à le faire pour explorer et améliorer vos compétences de prompt.
