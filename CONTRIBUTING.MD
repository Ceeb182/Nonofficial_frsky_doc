![Logo Dépos](Latest_release/_media/Logo-NonofficialFrSkydocuments-h41.png "Traductions de documents FrSky")  
[![Flag FR>](Latest_release/_media/Flag_FRh11.png "Français")](#FR_Section) **Bienvenue** / [Cliquez sur votre langue](#FR_Section)  
[![Flag EN>](Latest_release/_media/Flag_ENh11.png "English")](#EN_Section) **Welcome** / [Click on your language](#EN_Section)  

--------------------------------------------------------------------------------------
<a name="FR_Section"></a>![<MERCI>](Latest_release/_media/Logo-ThanksFR.png "Merci")

*Tout d'abord, merci pour le temps que vous donnez pour contribuer à l'amélioration des documents présents sur ce dépot !*

--------------------------------------------------------------------------------------

### ![<*>](Latest_release/_media/Logo-UnderConstruction25x22.png) CE DOCUMENT EST EN CONTRUCTION ![<*>](Latest_release/_media/Logo-UnderConstruction25x22.png)
# Voici quelques éléments pour vous guider dans votre contribution...

## Sommaire

[Charte Code de Conduite Contributeurs](#FR_COC)

[Soyez patient et indulgent](#FR_Patient)

[A qui dois-je faire part de mon souhait d'obtenir une traduction particulière ?](#FR_Wish)


Je souhaite :
- [soutenir cette initiative en faisant une don](#FR_Donate)
- [vérifier et corriger les traductions déjà réalisées : orthographe, grammaire, tournure de phrase...](#FR_Issue)
- [proposer de nouvelles traductions littérales sans m'occuper de la mise en page](#FR_TxtOnly)
- [proposer une partie graphique du document (dessin, schéma,...) au format SVG](#FR_Drawing)
- [proposer une traduction **intégrale** tant sur le fond que sur la forme](#FR_Integral)
- [proposer le travail actuel dans d'autres langues](#FR_TranslateOL)
- [mettre à disposition du contenu permettant la création des versions "`Plus`" ou "`Inédites`"](#FR_Plus)

[Opérations avec Git et GitHub](#FR_Workflow)
<BR>

<a name="FR_COC"></a>
## ![>](Latest_release/_media/Logo-PuceTriJN.png) Charte Code de Conduite Contributeurs
Ce projet et tous ceux qui y participent sont régis par un [code de conduite](CODE_OF_CONDUCT.MD). En participant, vous devez respecter ce code. Veuillez signaler tout comportement inacceptable à [ceeb182@laposte.net](ceeb182@laposte.net).

<a name="FR_Patient"></a>
## ![>](Latest_release/_media/Logo-PuceTriJN.png) Soyez patient et indulgent
C'est la première fois que je met en place et que j'utilise l'outil Git et les services de GitHub.  
Je ne suis ni programmeur, ni webmaster.  
J'apprends au fur et à mesure de l'évolution de ce projet.  
**Aussi, je vous remercie pour la patience et l'indulgence dont vous ferez preuve à mon égard.**
Je reste à l'écoute de vos conseils. Les documents décrivant chaque partie du projet (notammment les README.MD, CONTRIBUTING.MD) pourront évoluer.

<a name="FR_Wish"></a>
## ![>](Latest_release/_media/Logo-PuceTriJN.png) Demander une traduction particulière
Le plus simple pour la version Française est de faire votre souhait au sein du forum francophone FrSky : [http://frskytaranis.forumactif.org/](http://frskytaranis.forumactif.org/t4657-manuels-d-utilisation-frsky-traduits-en-francais). 
Evidemment la priorité sera donnée aux produits les plus demandés. 
N'oubliez pas que ces traductions sont réalisées par des bénévoles et qu'il faut en moyenne 8h de travail par page pour un manuel en version `Base`.

<a name="FR_Donate"></a>
## ![>](Latest_release/_media/Logo-PuceTriJN.png) Soutenir cette initiative en faisant un don
Vous souhaitez soutenir cette initiative  en faisant un don,  
vous en avez la possibilité en cliquant sur le lien suivant : [![<Donate Ceeb182>](Latest_release/_media/Logo-DonateCeeb182.png "Soutenir via CotizUp")](https://www.cotizup.com/ceeb182-nfd01/donation)

<a name="FR_Issue"></a>
## ![>](Latest_release/_media/Logo-PuceTriJN.png) Vérifier et corriger les traductions déjà réalisées


> **![>](Latest_release/_media/Logo-Important.png) A lire avant de commencer :**  
> 1. **Quels documents corriger ?**  
>    Vous ne devez vérifier que les documents PDF présents dans le répertoire "![>](Latest_release/_media/Logo-Folder.png) **Latest_release**" de la branche "*Master*".  
>    Il est inutile de vous occupez des autres documents.  
>    Il peut subsister des erreurs, même si un document a déjà été relu et/ou corrigé (consulter la note de version correspondant au document pour en savoir plus).
> 2. **Quel logiciel utiliser pour signaler les erreurs ?**  
>    Vous devez installer un logiciel gratuit pour **lire** et **commenter** les fichiers **PDF** :  
>    - Sous Windows, vous pouvez utliser [![>](Latest_release/_media/Logo-Foxit.png) **Foxit Reader**](https://www.foxitsoftware.com)  
>    - Sous Linux, vous pouvez utiliser [![>](Latest_release/_media/Logo-MasterPDFEditor.png) **Master PDF Editor**](https://code-industry.net/free-pdf-editor/) free edition  
> 3. **Comment signaler les erreurs ? Comment proposer des corrections ?**  
>    Chaque erreur est signalée avec le logiciel précédemment cité. 
>    Pour faire cela :
>    - Chaque erreur est entourée d'une ellipse rouge.
>    - Chaque erreur est commentée avec une note qui précise l'erreur et qui propose une correction.
>    
>    Une fois le fichier annoté, enregitrez-le sur votre ordinateur.
> 4. **Comment soumettre ma correction au dépôt ?**  
>    Il est impératif de suivre la procédure "**correction de document**".
>    Cette procédure permet :
>    - d'éviter les corrections en doublon
>    - d'historiser les corrections
>    - d'échanger sur la correction si nécessaire
>    - de joindre votre fichier annoté

### Procédure de "correction de document" :

1. **Avant de signaler un problème**, veuillez vérifier que ce problème n'a pas déjà été déclaré.  
   Pour le vérifier, cliquez sur l'onglet `Issue` et tapez dans le champ de recherche :
   * le nom complet du fichier
   * le mot clef "correction"
   
   Dans les résultats de recherche, vérifier que ce problème n'a pas déjà été déclaré.

2. **Si le problème n'a pas été déclaré**,  
   * Cliquer sur le bouton `New issue`.
   * Indiquer dans le titre de l'`Issue` *le nom complet du fichier* concerné **ET** le mot clef "Correction" (par exemple `X8R-Manuel utilisateur-vFr5.PDF`/**`Correction`**)  
   * Cliquer sur `selecting them` pour joindre le fichier PDF annoté des vos corrections à l'`Issue`  
   * Eventuellement écrire un texte d'accompagnement

3. **La prise en compte du problème** sera effective lorque cette `Issue` sera assignée à un correcteur
4. **La résolution du problème** sera effective lorsque cette `Issue` sera cloturée par l'Administrateur.

<a name="FR_TxtOnly"></a>
## ![>](Latest_release/_media/Logo-PuceTriJN.png) Proposer de nouvelles traductions littérales sans m'occuper de la mise en page

1. **Cas n°1 - Je ne sais pas utiliser Git et GitHub**  
   Vous pouvez proposer votre traduction littérale dans un fichier texte *à joindre* à une `Issue` directement sur GitHub. 
   - Cliquez sur le bouton `New issue`
   - Dans ce cas votre `Issue` doit se nommer : "`Nom du produit` / **`Translation`**"
   - Attribuer-vous cette `Issue`
   - En plus de votre message, en bas cliquez sur `selecting them` pour attacher votre fichier de traduction

   Note : Pour plus de clarté, vous pouvez formater votre fichier en *MarkDown* comme indiqué dans [ce guide](https://help.github.com/articles/basic-writing-and-formatting-syntax/).
2. **Cas n°2 - Je sais utiliser Git et GitHub**  
   Vous pouvez proposer le ou les fichiers de votre traduction littérale en effectuant une `Pull request` de votre branche de travail sur la branche `Next_release`, conformément à la procédure décrite dans **[Opérations avec Git et GitHub](#FR_Workflow)**.

<a name="FR_Drawing"></a>
## ![>](Latest_release/_media/Logo-PuceTriJN.png) Proposer une partie graphique du document (dessin, schéma,...) au format SVG
)

Les parties graphiques sont exclusivement réalisées avec le logiciel libre **Inkscape** et sont au format SVG. 
Assurez-vous d'utiliser la dernière version de ce logiciel sur http://www.inkscape.org/.

1. **Cas n°1 - Je ne sais pas utiliser Git et GitHub**  
   Vous pouvez proposer une partie graphique dans un fichier SVG *à joindre* à une `Issue` directement sur GitHub. 
   
   - Cliquez sur le bouton `New issue`
   - Dans ce cas votre `Issue` doit se nommer : "`Nom du produit` / **`Drawing`**"
   - Attribuer-vous cette `Issue`
   - En plus de votre message, en bas cliquez sur `selecting them` pour attacher votre partie graphique au format SVG

2. **Cas n°2 - Je sais utiliser Git et GitHub**  
   Vous pouvez proposer le ou les fichiers SVG en effectuant une `Pull request` de votre branche de travail sur la branche `Next_release`, conformément à la procédure décrite dans **[Opérations avec Git et GitHub](#FR_Workflow)**

<a name="FR_Integral"></a>
## ![>](Latest_release/_media/Logo-PuceTriJN.png) Proposer une traduction intégrale tant sur le fond que sur la forme

Vous êtes dans le cas où :
- vous avez collecté toutes les données pour réaliser une traduction intégrale
- vous maîtrisez les outils logiciels : Inkscape, Gimp, ZintBarCode, PDFtk
- vous formatez les documents en respectant les règles communes de conception
- vous respectez l'organisation du dépôt
- vous utilisez l'outil de versionning Git et GitHub.

Proposez cet ensemble de fichier en effectuant une `Pull request` de votre branche de travail sur la branche `Next_release`, conformément à la procédure décrite dans **[Opérations avec Git et GitHub](#FR_Workflow)**.

<a name="FR_TranslateOL"></a>
## ![>](Latest_release/_media/Logo-PuceTriJN.png) Proposer le travail actuel dans d'autres langues

**C'est le cas si une traduction en langue non-anglaise a déjà été réalisée**  
Vous trouverez dans le dossier **"Working_folder/`Dossier produit`/`Nom produit`-Source/`LANGUE`"** les fichiers de chaque page au format SVG. Ces fichiers sont éditables avec Inkscape.
1. **Cas n°1 - Je ne sais pas utiliser Git et GitHub**  
   Vous pouvez proposer votre traduction de chaque fichier SVG *en pièce jointe* à une `Issue` directement sur GitHub.  
   - Cliquez sur le bouton `New issue`
   - Dans ce cas votre `Issue` doit se nommer : "`Nom du produit` / **`Translation`**"
   - Attribuer-vous cette `Issue`
   - En plus de votre message, en bas cliquez sur `selecting them` pour attacher votre page nouvellement traduite au format SVG.  
2. **Cas n°2 - Je sais utiliser Git et GitHub**
  Vous pouvez proposer le ou les traductions au format SVG en effectuant une `Pull request` de votre branche de travail sur la branche `Next_release`, conformément à la procédure décrite dans **[Opérations avec Git et GitHub](#FR_Workflow)**  

<a name="FR_Plus"></a>
## ![>](Latest_release/_media/Logo-PuceTriJN.png) Mettre à disposition du contenu permettant la création des versions "`Plus`" ou "`Inédites`"

Pour réaliser les versions "`Plus`" ou "`Inédites`", il est nécessaire d'avoir des informations complémentaires vérifiées.  
Il peut s'agir par exemple :
- de visuels du produit plus pertinent que la représentation de base 
- de procédures particulières non décrites officiellement
- d'explication sur des mises en oeuvres particulières
- de légendes de broches initialement non documentées
- de rectification d'erreurs exceptionnelles sur le manuel original
- etc...

Cet ensemble de données complémentaire peut donc être : des photos, des liens vers des forums de discussion spécialisés, des liens vers des Datasheet de composant, etc...  
Dans la mesure du possible, écrire ou joindre un message indiquant :  
- comment utiliser ces informations
- comment vous avez recoupé les informations.  


1. **Cas n°1 - Je ne sais pas utiliser Git et GitHub**  
   Vous pouvez proposer ces informations complémentaires sous la forme d'une archive *à joindre* à une `Issue` directement sur GitHub. 
   
   - Cliquez sur le bouton `New issue`
   - Dans ce cas votre `Issue` doit se nommer : "`Nom du produit` / **`New_news`**"
   - Attribuer-vous cette `Issue`
   - En plus de votre message, en bas cliquez sur `selecting them` pour attacher une archive de vos documents.

2. **Cas n°2 - Je sais utiliser Git et GitHub**  
   Vous pouvez proposer le ou les informations complémentaires en effectuant une `Pull request` de votre branche de travail sur la branche `Next_release`, conformément à la procédure décrite dans **[Opérations avec Git et GitHub](#FR_Workflow)**

<a name="FR_Workflow"></a>
## ![>](Latest_release/_media/Logo-PuceTriJN.png) Opérations avec Git et GitHub

*La gestion du flux de travail est très largement inspirée du projet [OpenTx](https://github.com/opentx/opentx/wiki/Github-issue-workflow).*
  >   ![>](Latest_release/_media/Logo-warning.png) **IMPORTANT :**  
  >   - Vous ne devez **jamais** travailler sur la branche **MASTER**
  >   - Vous ne devez **jamais** pousser vos travaux **directement** sur la branche **Next_release**
  >   - Respecter la convention pour nommer votre nouvelle branche
  >   - Respecter l'arborescence du projet : voir [Organisation du dossier "Working_folder"](Working_folder/README.MD)
   
   1. Chaque contributeur commence par créer une version locale du dépôt `Master`.
   2. Chaque nouvelle contribution doit commencer par la création d'une `Issue` sur GitHub pour obtenir un numéro identifiant unique (par exemple `#27`). Si une convention existe pour nommer le titre de votre `Issue`, veuillez la respecter.
   3. Attribuer-vous cette `Issue`. 
   4. Créer une nouvelle branche, sur votre dépôt local, qui devra être nommmée **`YourGitHubName/name_of_the_issue_27`**
   5. Positionnez-vous sur cette nouvelle branche de votre dépôt local
   6. Ajouter le cas échéant l'arborescence manquante (voir [Organisation du dossier "Working_folder"](Working_folder/README.MD)). Si c'est une toute nouvelle traduction, il y a de forte chance que le dossier correspondant n'existe pas encore.
   7. **Sur votre branche locale, créer/modifier le ou les fichiers correspondant à votre `Issue`**
   8. Sur votre branche locale, indexer et commmiter vos nouveaux fichiers avec un message débutant par #27 puis votre message (si #27 est l'identifiant de l'`Issue`).  
   Le dernier de vos `commit` doit comporter la mention `Fixed #27` inclus dans le message. Cette dénomination augmentera les chances que l'administrateur remarque que votre travail est prêt à être fusionné (`merge`). 
   9. Pousser votre branche sur GitHub
   10. Sur GitHub, cliquez sur `Compare & Pull Request`. Cette demande doit être paramétrée entre **votre branche** et **la branche `Next_release`** (Ne pas faire cette demande avec la branche `Master` qui est la branche par défaut)
   11. Lorsque cette modification est acceptée par l'Administrateur, vos nouveaux fichiers sont fusionnés à la branche `Next_release`. L'administrateur supprimera sur GitHub la branche temporaire à votre nom.
   12. L'administrateur fermera le numero `Issue` correspondant
   13. Lorsque l'administrateur fusionnera (`Merge`) la branche `Next_release` avec `Master`, vos documents feront désormais partis de la prochaine diffusion publique.

*CONTRIBUTING.MD / Mis à jour 31-10-2017*
<BR>
<BR>
<BR>

--------------------------------------------------------------------------------------
<a name="EN_Section"></a>![<THANKS>](Latest_release/_media/Logo-ThanksEN.png "Thanks")

*First off, thank you for the time that you give to contribute to the improvement of the documents present on the repository !*

--------------------------------------------------------------------------------------

### ![<*>](Latest_release/_media/Logo-UnderConstruction25x22.png) THIS DOCUMENT IS UNDER CONTRUCTION ![<*>](Latest_release/_media/Logo-UnderConstruction25x22.png)
# Here are some elements to guide you in your contribution...

## Table Of Contents

[Charter Code of Conduct Contributors](#EN_COC)

[Be patient and indulgent](#EN_Patient)

[To whom should I express my wish to obtain a particular translation?](#EN_Wish)

I would like :
- [support this initiative by making a donation](#EN_Donate)
- [to check and to correct already translated documents : spelling, grammar, sentences sense...](#EN_Issue)
- [to propose new literal translations without taking care of the layout](#EN_TxtOnly)
- [to propose a graphical part of the document (drawing, diagram, ...) in SVG format](#EN_Drawing)
- [to propose a **complete** translation both on the substance and on the form](#EN_Integral)
- [to propose the current work in other languages](#EN_TranslateOL)
- [to make content available for creating "`Plus`" or "`Unpublished`"](#EN_Plus)

[Git and GitHub workflow](#EN_Workflow)
<BR>

<a name="EN_COC"></a>
## ![>](Latest_release/_media/Logo-PuceTriJN.png) Code of Conduct Charter
This project and everyone participating in it is governed by a [code of conduct](CODE_OF_CONDUCT.MD). By participating, you are expected to uphold this code. Please report unacceptable behavior to [ceeb182@laposte.net](ceeb182@laposte.net).


<a name="EN_Patient"></a>
## ![>](Latest_release/_media/Logo-PuceTriJN.png) Be patient and indulgent
This is the first time I have set up and used the Git tool and GitHub services.  
I am neither a programmer nor a webmaster.  
I learn as the project progresses.  
**So I thank you for the patience and indulgence you will show me.**  
Documents describing each part of the project (including README.MD, CONTRIBUTING.MD) will evolve.


<a name="EN_Wish"></a>
## ![>](Latest_release/_media/Logo-PuceTriJN.png) Ask for a specific translation
The simplest for the French version is to make your wish in the FrSky French forum : [http://frskytaranis.forumactif.org/](http://frskytaranis.forumactif.org/t4657-manuels-d-utilisation-frsky-traduits-en-francais).  
For other languages, open a new issue named "`Translation request / name_of_the_source_document`" and indicate in the message the exact location of the document to be translated and the desired translation language.  
Obviously, priority will be given to the most requested products.  
Remember that these translations are carried out by volunteers and that it takes an average of 8 hours of work per page for a manual in the `Base` version.  

<a name="EN_Donate"></a>
## ![>](Latest_release/_media/Logo-PuceTriJN.png) Support this initiative by making a donation
You wish to support this initiative by making a donation,  
you can do so by clicking on the following link : [![<Donate Ceeb182>](Latest_release/_media/Logo-DonateCeeb182.png "Support via CotizUp")](https://www.cotizup.com/ceeb182-nfd01/donation)


<a name="EN_Issue"></a>
## ![>](Latest_release/_media/Logo-PuceTriJN.png) Check and correct already translated documents

> **![>](Latest_release/_media/Logo-Important.png) Read before you start :**  
> 1. **What are the documents to correct ?**  
>    You only need to check PDF documents in the "**Latest_release**" directory of the "*Master*" branch..  
>    There is no point in dealing with other documents.  
>    There may still be errors, even if a document has already been re-read and/or corrected (see the release note for the document for more information).

> 2. **Which software to use to report errors ?**  
>    You need to install free software to **read** and **comment** **PDF** files:  
>    - On Windows, you can use [![>](Latest_release/_media/Logo-Foxit.png) **Foxit Reader**](https://www.foxitsoftware.com)  
>    - On Linux, you can use [![>](Latest_release/_media/Logo-MasterPDFEditor.png) **Master PDF Editor**](https://code-industry.net/free-pdf-editor/) free edition  
> 3. **How to report errors ? How to propose corrections ?**  
>    Each error is reported with the software mentioned above. 
>    To do that :
>    - Each error is surrounded by a red ellipse.
>    - Each error is commented with a note that specifies the error and that proposes a correction.
>    
>    Once the file is annotated, save it to your computer.
> 4. **How to submit my correction to the repository ?**  
>    It is imperative to follow the "**document correction**" procedure.  
>    This procedure allows:
>    - do not perform a duplicate correction
>    - to log corrections
>    - to discuss the correction if necessary
>    - to attach your annotated file

### "Document correction" procedure :

1. **Before reporting an issue** on an existing document, make sure that this issue has not already been reported.  
   To check it, click on the `Issue` tab and type in the search field:  
   * the full name of the file concerned
   * the key word "correction"
   
   In the search results, verify that this issue has not already been reported.

2. **If the issue has not been reported**
   * Click the `New issue` button.
   * Indicate in the title the *full name of the file* concerned **AND** the key word "correction" (for example `X8R-User Manual-vFr5.PDF`/**`Correction`**).  
   * Click on `selecting them` to attach the annotated PDF file of your corrections to your `Issue`
   * Possibly write a text to explain what you want to correct

3. **Taking into account the problem** will be effective when this `Issue` will be assigned to a corrector
4. **The problem will be solved** when this Issue is closed by the Administrator.


<a name="EN_TxtOnly"></a>
## ![>](Latest_release/_media/Logo-PuceTriJN.png) Propose new literal translations without taking care of the layout

1. **Case 1 - I do not know how to use Git and GitHub**  
   You can submit your literal translation in a text file *to be attached* to a `Issue` directly on GitHub.  
   - Click the `New issue` button
   - In this case your `Issue` should be named: `Product name` / **`Translation`** "
   - Assign you this `Issue`
   - In addition to your message, at the bottom, click `selecting them` to attach your translation file

   Note : For ease of reading, you can format your *MarkDown* file as shown in this [guide](https://help.github.com/articles/basic-writing-and-formatting-syntax/).
2. **Case 2 - I know how to use Git and GitHub**  
   You can propose the file(s) of your literal translation by performing a `Pull request` from your branch to the `Next_release` branch, as described in **[Git and GitHub workflow](#EN_Workflow)**.


<a name="EN_Drawing"></a>
## ![>](Latest_release/_media/Logo-PuceTriJN.png) Propose a graphical part of the document (drawing, diagram, ...) in SVG format


The graphic parts are exclusively made with the free software **Inkscape** and are in SVG format. 
Be sure to use the latest version of this software at http://www.inkscape.org/.

1. **Case 1 - I do not know how to use Git and GitHub**  
   You can propose a graphical part in an SVG file *to be attached* to an `Issue` directly on GitHub.  
   - Click the `New issue` button
   - In this case your `Issue` should be named: `Product name` / **`Drawing`**"
   - Assign you this `Issue`
   - In addition to your message, at the bottom, click `selecting them` to attach your graphic part in SVG format
  
2. **Case 2 - I know how to use Git and GitHub**  
   You can propose the SVG file(s) by performing a `Pull request` from your branch to the `Next_release` branch, as described in **[Git and GitHub workflow](#EN_Workflow)**.


<a name="EN_Integral"></a>
## ![>](Latest_release/_media/Logo-PuceTriJN.png) Propose a complete translation both on the substance and on the form

You are in the event that :
- you have collected all the data to make a complete translation
- you master the software tools : Inkscape, Gimp, ZintBarCode, PDFtk
- you format the documents according to the common design rules
- you respect the organization of the repository
- you use the GitHub and Git versioning tool.

Propose this file set by performing a `Pull request` from your branch to the `Next_release` branch, as described in **[Git and GitHub workflow](#EN_Workflow)**.


<a name="EN_TranslateOL"></a>
## ![>](Latest_release/_media/Logo-PuceTriJN.png) Propose the current work in other languages

**This is the case if a translation into non-English language has already been performed**  
You will find in the folder **"Working_folder/`Product directory`/`Product name`-Source/`LANGUAGE`"** the files of each page in SVG format. These files can be edited with Inkscape.
1. **Case 1 - I do not know how to use Git and GitHub**  
   You can submit your translation of each SVG file as *an attachment* to an `Issue` directly on GitHub.  
   - Click the `New issue` button
   - In this case your `Issue` should be named: `Product name` / **`Translation`**"
   - Assign you this `Issue`
   - In addition to your message, click `selecting them` to attach your newly translated page to SVG format.  
2. **Case 2 - I know how to use Git and GitHub**  
  You can propose the translation(s) in SVG format by performing a `Pull request` from your branch to the `Next_release` branch, as described in **[Git and GitHub workflow](#EN_Workflow)**.  


<a name="EN_Plus"></a>
## ![>](Latest_release/_media/Logo-PuceTriJN.png) Make content available for creating "`Plus`" or "`Unpublished`"

To make "Plus" or "Unpublished" versions, it is necessary to have verified additional information.  
For example, this may include:
- visuals of the product more relevant than the basic representation 
- particular procedures not officially described
- explanations on specific implementations
- the initially undocumented pin legends
- a rectification of exceptional errors on the original manual
- etc.

This complementary dataset can consist of: photos, web links to specialized discussion forums, links to the component's Datasheet, etc.
Whenever possible, write or attach a message indicating:  
- how to use this information  
- how you intersected the information.  


1. **Case 1 - I do not know how to use Git and GitHub**  
   You can provide this additional information in the form of an *attachment* archive to an `Issue` directly on GitHub.
   
   - Click the `New issue` button
   - In this case your `Issue` should be named: `Product name` / **`New_news`**"
   - Assign you this `Issue`
   - In addition to your message, click `selecting them` to attach an archive file of your documents.

2. **Case 2 - I know how to use Git and GitHub**  
   You can propose the additional information by performing a `Pull request` from your branch to the `Next_release` branch, as described in **[Git and GitHub workflow](#EN_Workflow)**.  


<a name="EN_Workflow"></a>
## ![>](Latest_release/_media/Logo-PuceTriJN.png) Git and GitHub workflow

*This workflow is largely inspired by the [OpenTx](https://github.com/opentx/opentx/wiki/Github-issue-workflow) project*
  >   ![>](Latest_release/_media/Logo-warning.png) **WARNING :**  
  >   - You must **never** work on the branch **MASTER**  
  >   - You should **never** push your jobs **directly** on the **Next_release** branch  
  >   - Respect rules for naming your new branch
  >   - Respect the management of project files (tree structure) : see [Management of the "Working_folder"](Working_folder/README.MD)

   1. Each committer starts by creating a local version of the master repository.
   2. Each new contribution must start with the creation of a `Issue` on GitHub to get a unique identifier number (for example`#27`). If a rule exists to name the title of your Issue, please respect it.
   3. Assign you this `Issue`.
   4. Create a new branch, on your local repository, which should be named **`YourGitHubName / name_of_the_issue_27`**
   5. Position yourself on this new branch of your local repository.
   6. If necessary, add the missing directories (see [Management of the "Working_folder"](Working_folder/README.MD)). If it is a brand new translation, there is a good chance that the corresponding file does not yet exist.
   7. **On your local branch, create / modify the file(s) corresponding to your `Issue`**
   8. On your local branch, add and commit your new files with a message starting with #27 then your message (if #27 is the identifier of the `Issue`).
   The last of your `commit` must contain `Fixed #27` included in the message. This denomination will increase the chances that the administrator will see that your job is ready to `merge`.  
   9. Push your branch on GitHub
   10. On GitHub, click `Compare & Pull Request`. This request must be set between **your branch** and **the branch `Next_release`** (Do not make this request with the branch `Master` which is the default branch)
   11. When this change is accepted by the Administrator, your new files are merged with the `Next_release` branch. The administrator will delete on GitHub this temporary branch that is in your name.
   12. The administrator will close the corresponding `Issue` number
   13. When the administrator merges the branch` Next_release` with `Master`, your documents will now be part of the next public release.

*CONTRIBUTING.MD / Updated 31-10-2017*
<BR>
<BR>