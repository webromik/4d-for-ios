---
id: many-to-one-relations
title: Liens N vers 1
---

4D v17 R5 lance un nouveau concept : les liens N vers 1<div class = "tips"> 

**NOTE**

Dans ce tutoriel, nous allons utiliser les noms des liens reliant vos tables. En attribuant des noms de liens descriptifs, vous simplifierez la structure de votre projet.</div> 

Commençons par télécharger le Projet Starter :

<div style="text-align: center; margin-top: 20px; margin-bottom: 20px">
  <p>
    

<a class="button"
href="https://github.com/4d-for-ios/tutorial-ManyToOneRelations/releases/latest/download/tutorial-ManyToOneRelations.zip">PROJET STARTER N VERS UN</a>

  </p>
</div>

Nous souhaitons afficher ici la catégorie de chaque tâche dans le formulaire détaillé de votre application. Pour ce faire, ouvrez le **StarteriOSProject** à partir de **Ouvrir > Projet mobile...**

Accédez directement à la section Structure, puis sélectionnez la **table Tasks**.

### Section Structure

* Vous pouvez constater que le **lien TaskCategory** est souligné

* En cliquant dessus, vous afficherez les champs disponibles à travers ce lien

* Sélectionnez le **champ Name**

![Select link from structure section](assets/en/relations/select-link-from-structure.png)

* Ce champ aura le même fonctionnement que n’importe quel autre champ pour la suite de la création de l’application

* Vous pouvez également filtrer le contenu de votre application à l’aide des champs liés, à partir de la section Données. Pour ce faire, saisissez ```TaskCategory.Name != 'Personal'``` dans le filtre de requête, pour exclure les tâches de type "Personal".
    
    ![Champs liés depuis la section Données](assets/en/relations/Related-field-from-Data-section.png)

* Vous pouvez ensuite sélectionner une **icône** et des **formats** et définir des **libellés courts et longs** dans la section Libellés et icônes

![Related field from Labels and Icons section](assets/en/relations/related-field-from-labels-icons.png)

* Cliquez sur la section Formulaires et faites glisser le champ dans le formulaire détaillé Tasks

![Related field in Forms section](assets/en/relations/related-field-forms.png)

* Créer & exécuter

Votre champ lié devrait apparaitre dans le formulaire détaillé de votre application !

![Related field in Forms section](assets/en/relations/final-result-n-to-one-relations.png)